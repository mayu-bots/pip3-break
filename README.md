# pip3-break

#### Force pip3 install on system-wide (Python >= 3.12)

--------------------------
Copy & run command then do pip3 install normally
```
echo -e "[global]\nbreak-system-packages = true" >> /etc/pip.conf
```
