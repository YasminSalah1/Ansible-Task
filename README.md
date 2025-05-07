# Ansible-Task
# My website
# Install_Apache Ansible Role

Ansible role to install and configure Apache (httpd) web server on RHEL/CentOS systems, change its default port from *80 to 88*, and upload a test web page
# My website
![image](https://github.com/user-attachments/assets/818f9323-dfe3-4242-84e3-de5db190504b)


---

## 📌 Role Features

•⁠  ⁠Install Apache (⁠ httpd ⁠)
•⁠  ⁠Enable and start Apache service
•⁠  ⁠Backup the original ⁠ httpd.conf ⁠ file
•⁠  ⁠Change Apache listen port from ⁠ 80 ⁠ to ⁠ 88 ⁠
•⁠  ⁠Update SELinux to allow port 88
•⁠  ⁠Open port 88 in ⁠ firewalld ⁠
•⁠  ⁠Upload custom ⁠ index.html ⁠ page
•⁠  ⁠Handler to restart Apache after changes

---

## 📁 Role Structure

Install_Apache/
├── defaults/
│   └── main.yml
├── files/
|   └── index.html
├── handlers/
│   └── main.yml
├── meta/
│   └── main.yml
├── tasks/
│   └── main.yml
├── tests/
│   └── test.yml
├── vars/
│   └── main.yml
└── .travis.yml

---

