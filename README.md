# LampStackImplementation

1. First, a new EC2 Ubuntu instance called 'LAMP Proj' was created in AWS as shown below.

![EC2 instance](https://github.com/oghare01/LampStackImplementation/assets/141191975/7d0b8009-c0eb-4705-9c47-9f57a2897514)

2. Then I opened up Git Bash to connect to the AWS instance which successfully connected to the AWS server which can be seen in the below screenshot

![EC2 connected successfuly](https://github.com/oghare01/LampStackImplementation/assets/141191975/41da4497-23c5-4884-bf19-4c3d651fb6db)

3. Next, I installed Apache web server and confirmed that is was running successfully. The test revealed that Apache was up and running as displayed in the following image.

![Apache up and running](https://github.com/oghare01/LampStackImplementation/assets/141191975/e407acbb-4687-415a-afed-4e1d781032c2)

4. I used the curl command to test the Apache server and it gave the expected result

![Curl result](https://github.com/oghare01/LampStackImplementation/assets/141191975/76f84857-5782-49f0-966d-bfe9efed2511)

5. Next I checked the server on a browser which resulted in the image displayed below

![public address works!](https://github.com/oghare01/LampStackImplementation/assets/141191975/41f98f07-e35f-466e-a009-e597166e0852)

6. Mysql was installed and tested. The result showed that mysql was properly installed and running

![Mysql installed and running](https://github.com/oghare01/LampStackImplementation/assets/141191975/e134ddf4-2a86-4507-9454-0ee10bab1b70)

7. I changed the password and exited mysql

![mysql password changed and exited ](https://github.com/oghare01/LampStackImplementation/assets/141191975/4860f0ef-c0fc-424c-b9e8-78a20b784caf)

8. I validated the password for mysql server

![Password validation](https://github.com/oghare01/LampStackImplementation/assets/141191975/c3662429-d11e-4c32-8b9d-66fce737ed2e)

9. PHP was successfully installed and the version was checked using the php -v command

![php installed ](https://github.com/oghare01/LampStackImplementation/assets/141191975/eac4978e-4b59-49ad-a2b7-f891aa0dc5b9)

10. The virtual host for the website was created as shown below

![virtualhost created](https://github.com/oghare01/LampStackImplementation/assets/141191975/58364bed-ae72-4f8c-9ee2-a7eb6589511b)

11. A new virtuall host was enable and the default website was disabled. The configuration test revelaed the below display

![new virtual host enabled](https://github.com/oghare01/LampStackImplementation/assets/141191975/d7d3dcba-57cf-4b10-9ddc-7b01379f80e3)

12. Apache2 was reloaded, the website was edited and when I reloaded it worked just fine

![relaoded webpage](https://github.com/oghare01/LampStackImplementation/assets/141191975/d54372a7-dfe4-40a7-b3c2-d160c1d840c2)
