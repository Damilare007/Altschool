 1)creating a user called Damilare\
sudo useradd Damilare
![the terminal](./Screenshot%20(90).png)

2)setting expiry date of user Damilare to two weeks (31-08-2023)\
sudo usermod -e 2023-08-31 Damilare  \
3) i prompted the user to change password on login\
sudo passwd -e Damilare \
4)I created the altchool group and appended user Damilare to the group \
sudo groupadd altschool\
sudo usermod -aG altschool Damilare  \
![the terminal](./Screenshot%20(89).png)
5)Allowing altschool group to be able to run only cat on /etc
![the terminal](./Screenshot%20(91).png)

6)creating another user Eminent that doesn't have home directory\
![the terminal](./Screenshot%20(92).png)