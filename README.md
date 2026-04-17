# pip3-break

#### Force pip3 install on system-wide (Python >= 3.12)

--------------------------
Add default config then do pip3 install normally
```
echo -e "[global]\nbreak-system-packages = true" >> /etc/pip.conf
```
