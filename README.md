## Vision-Cursor, a minimalist cursor

![1F9E84AD-6882-41E0-86F4-EEBBC9BD7F58](https://github.com/N3bulaX/Vision-Cursor/assets/117851699/3a7d6b72-c5d2-4a79-8383-8fd392788c70)

# Installation Guide:

<details>
<summary>
    Windows
</summary>
 
 ###  Step 1 Once you've downloaded the compressed file, unzip it.

   ![Step 1](https://github.com/N3bulaX/Vision-Cursor/assets/117851699/8dbf340e-8db0-4d65-8206-157605e80e31)

 ###  Step 2 Open the unzipped folder.
       
   ![Step 2](https://github.com/N3bulaX/Vision-Cursor/assets/117851699/702eef7f-f453-4769-a248-0c1ddbace374)

 ### Step 3 Click "Install" and accept the installation option.

   ![Step 3](https://github.com/N3bulaX/Vision-Cursor/assets/117851699/1e131870-7d57-4c1e-bb2b-170ee57e0c54)
   ![Step 3 - Continued](https://github.com/N3bulaX/Vision-Cursor/assets/117851699/501bb2c9-466e-4e4b-ae0e-9618e55f0403)

 Confirm the installation, and the changes will be applied correctly.

</details>

<details>
<summary>
    Linux 
</summary>
    
extract `vision.cursor.tar.gz`

```bash
tar -xvf vision.cursor.tar.gz
```
Move the extracted folder to `icons` folder, change `<color>` to `black` or `white`
```bash
mv visioncursor<color> ~/.icons/        	       # Install to local users
sudo mv visioncursor<color> /usr/share/icons/      # Install to all users
```

Now, change your cursor using Gnome, or other manager

</details>

# Uninstallation Guide
<details>
 <summary>
    Linux
 </summary>

Uninstallation
```bash
rm ~/.icons/visioncursor<color>                  # Remove from local users
sudo rm /usr/share/icons/visioncursor<color>     # Remove from all users
```

</details>
