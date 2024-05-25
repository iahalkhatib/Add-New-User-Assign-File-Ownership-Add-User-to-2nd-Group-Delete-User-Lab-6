![image](https://github.com/iahalkhatib/Add-New-User-Assign-File-Ownership-Add-User-to-2nd-Group-Delete-User-Lab-6/assets/170050432/de6fd28c-8c15-4eff-8098-7feb351dccad)


# Add-New-User-Assign-File-Ownership-Add-User-to-2nd-Group-Delete-User-Lab-6

# 1. I will add a new user using "sudo useradd researcher9" and add the new user to the "research_team" group using "sudo usermod -g research_team researcher9"

![image](https://github.com/iahalkhatib/Add-New-User-Assign-File-Ownership-Add-User-to-2nd-Group-Delete-User-Lab-6/assets/170050432/0689d805-94bd-4e00-8e66-67aecf99d6d0)

# 2. I will assign the new user file ownership using "sudo chown researcher9 /home/researcher2/projects/project_r.txt"

![image](https://github.com/iahalkhatib/Add-New-User-Assign-File-Ownership-Add-User-to-2nd-Group-Delete-User-Lab-6/assets/170050432/b0aa1efe-5871-4e0a-9b78-951118fa6c92)

# 3. I will add the new user to a secondary group "sales_team" while maintaing original group "research_team" using "sudo usermod -a -G sales_team researcher9"

![image](https://github.com/iahalkhatib/Add-New-User-Assign-File-Ownership-Add-User-to-2nd-Group-Delete-User-Lab-6/assets/170050432/3c13b1a2-d043-4621-9819-6446fdc5ff43)

# 4. I will delete the new user but will get a error and so I must delete the group with the same name using "sudo userdel researcher9" and "sudo groupdel researcher9"

![image](https://github.com/iahalkhatib/Add-New-User-Assign-File-Ownership-Add-User-to-2nd-Group-Delete-User-Lab-6/assets/170050432/d44e1103-e49d-49f4-ada6-572dd0777e99)
