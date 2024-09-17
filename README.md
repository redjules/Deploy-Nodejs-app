# Deploy Nodejs app


<img width="1241" alt="Screenshot 2024-02-28 at 02 26 54" src="https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/45c4b504-f10f-4ffd-bbfb-93c1089a7879">

we go to Digital Ocean and create a Droplet:


<img width="1259" alt="Screenshot 2024-02-28 at 02 27 43" src="https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/3752680b-9a5c-4040-9529-2a5c1b795f35">



<img width="1011" alt="Screenshot 2024-02-28 at 02 28 05" src="https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/96248502-ca45-425b-a5b0-336e59beeedf">


we write the deploy-node.yaml playbook:

![Screenshot 2024-02-28 at 09 37 24](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/e21a4a88-7642-4428-bff4-0f402b6ecc31)

we deploy now the playbook:

![Screenshot 2024-02-28 at 09 43 24](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/c3d2414d-6d76-41cc-838c-bcb4cfa79f23)


we create the next task: Install dependencies


![Screenshot 2024-02-28 at 10 27 38](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/58dad69a-85b2-4202-90f6-99a4d83b5a0b)

The advantage of Ansible vs Python:

![Screenshot 2024-02-28 at 10 34 48](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/98ec8db1-73bc-4224-bc79-f84645697a8f)

we create a new user:

![Screenshot 2024-02-28 at 10 37 39](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/64af70d9-1275-44eb-8a6e-a935e1b98844)


and change the destination:

![Screenshot 2024-02-28 at 10 38 37](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/5f38f3cd-2752-4b7a-a02f-07a8cf12ec0e)

and we enable become user:

![Screenshot 2024-02-28 at 10 39 29](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/db22884a-2bf0-4554-8d0f-88a19d6d0e09)

![Screenshot 2024-02-28 at 10 41 12](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/bb748017-0888-48ca-8bd7-f6ab7dfb8113)

we execute the playbook:

![Screenshot 2024-09-17 at 22 57 48](https://github.com/user-attachments/assets/ed194ee8-ebfa-4588-8c24-8fda73460d6c)


the node server is running on the new user:

![Screenshot 2024-02-28 at 10 42 40](https://github.com/redjules/Deploy-Nodejs-app/assets/106017493/6289d922-1bd4-4ec6-a010-2e7fe06c887f)
