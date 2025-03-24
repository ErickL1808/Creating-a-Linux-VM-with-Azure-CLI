<h1>Deployment and Configuration Steps</h1>
<h3 align="center"> Head to Azure (http://shell.azure.com)</h3>
<h3 align="center"> or Click on "Cloud Shell" </h3>

![Screenshot 2025-03-24 130628](https://github.com/user-attachments/assets/b2801f75-370b-48a8-aa9a-949fd03cfb4e)
<br>
<br/>

From Cloud Shell, run the "az vm create" command & specify your own parameters & VM name (EL-LinuxVM)
![Screenshot 2025-03-24 131246](https://github.com/user-attachments/assets/7d91c0e5-204f-479d-bcee-76710b779827)
![Screenshot 2025-03-24 122238](https://github.com/user-attachments/assets/12800021-18dd-4ec0-8bcc-10790eda7702)
<br>
<br/>

Run the "az vm extension set" command to configure Nginx on your VM
![Screenshot 2025-03-24 123020](https://github.com/user-attachments/assets/0b6ce0d3-bb5b-4a7e-b26f-52e0332fb067)
![Screenshot 2025-03-24 123034](https://github.com/user-attachments/assets/193465f3-d2cb-4875-81fc-fcb35fa4d9fa)
![Screenshot 2025-03-24 123257](https://github.com/user-attachments/assets/283412b8-40da-4ce8-aed2-eb8c934036fd)
<br>
<br/>

Now that your Virtual Machine is created. Lets go connect and access the VM

![Screenshot 2025-03-24 123445](https://github.com/user-attachments/assets/179c2b64-10de-4f93-92a1-a8cff3977547)
![Screenshot 2025-03-24 123543](https://github.com/user-attachments/assets/3d601584-42e8-48a8-b556-37b89d6fab9f)
![Screenshot 2025-03-24 123834](https://github.com/user-attachments/assets/9ef79c60-a955-4d77-b852-1160bbcb066d)
![Screenshot 2025-03-24 124001](https://github.com/user-attachments/assets/9067480a-f7f3-4363-a89f-a6d40579f0c4)
<br>
<br/>

![Screenshot 2025-03-24 125053](https://github.com/user-attachments/assets/ac4f384f-b589-44cf-91a8-ff437cdac0fe)

<h1>
  Don't forget to clean up your environmnent
</h1>

- Close or delete any RGs or VMs , and verify deletion so that you don't incur unnecessary charges
- It's a good idea at the end of a project to identify whether you still need the resources you created. Resources that you leave running can cost you money. You can dellocate the VM or delete the resource group to delete the entire set of resources









