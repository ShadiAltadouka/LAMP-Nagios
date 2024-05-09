# LAMP-Nagios

.
├── host_vars
│   ├── ec2-100-27-232-140.compute-1.amazonaws.com.yml
│   ├── ec2-34-228-143-149.compute-1.amazonaws.com.yml
│   ├── ec2-34-229-203-4.compute-1.amazonaws.com.yml
│   └── ec2-54-175-46-155.compute-1.amazonaws.com.yml
├── inventory
├── lamp-playbook.yml
├── nagios-playbook.yml
├── README.md
└── roles
    ├── apache2-httpd
    │   ├── handlers
    │   │   └── main.yml
    │   ├── tasks
    │   │   ├── copy_code.yml
    │   │   └── main.yml
    │   └── templates
    │       └── index.php.j2
    ├── mysql
    │   ├── handlers
    │   │   └── main.yml
    │   ├── tasks
    │   │   └── main.yml
    │   └── templates
    │       └── my.cnf.j2
    └── php
        ├── handlers
        │   └── main.yml
        └── tasks
            └── main.yml
