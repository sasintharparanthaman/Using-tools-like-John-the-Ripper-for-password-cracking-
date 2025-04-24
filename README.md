# EXP 7 :USING JOHN THE RIPPER FOR PASSWORD CRACKING

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## EQUIPMENTS REQUIRED:
●	Hardware: PCs

```
Register Number: 212223230199
Name: SASINTHAR P
```

## DESIGN STEPS:
### Step 1:
Install John the Ripper in Kali linux

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).

### Step 3:
Use John the Ripper to crack the hashes

## PROCEDURE:
### Step 1: Create a Text File

  •	Right-click on the Desktop and choose Create Document → Empty Document.
  
  •	Name the file: sachin

![Screenshot 2025-04-24 143848](https://github.com/user-attachments/assets/ac353326-f849-4748-85d3-03489fa7c3e6)


  •	Open it and type:

 ![Screenshot 2025-04-24 144014](https://github.com/user-attachments/assets/755ea71a-6324-4fe3-af7c-2180503c3c5e)



  •	Save and close the file.

### Step 2: Create a Password-Protected ZIP File

  •	Right-click on sachin.txt → Create Archive.
  

![Screenshot 2025-04-24 142747](https://github.com/user-attachments/assets/2b466064-54d5-492f-811b-d0fc075c19eb)


  •	Select .zip format.
  
  •	Click Other Options, set a password (e.g., 1234), then click Create.
  
![Screenshot 2025-04-24 142910](https://github.com/user-attachments/assets/3be89cb2-3c58-4267-be15-84545a277e97)



  •	A file named sachin.txt.zip will appear.

### Step 3: Open John the Ripper Terminal in Kali Linux

  •	Click on the Kali menu or press the Super (Windows) key.
  
  •	Search for “john” and click it — this opens the terminal with John the Ripper installed.
  

![Screenshot 2025-04-24 142941](https://github.com/user-attachments/assets/f6b7a67a-3cf1-4171-80d9-cf4af9511a06)


  •	Or simply open a Terminal from the dock or desktop.

### Step 4: Navigate to the File Location

  •	In the terminal, switch to the Desktop where the ZIP file is located:
  
![Screenshot 2025-04-24 143020](https://github.com/user-attachments/assets/e9b273e2-0c9a-4142-9e02-dd783b15fd86)



### Step 5: Confirm the ZIP File is Present

  •	Run: “ls” command
  
![Screenshot 2025-04-24 143044](https://github.com/user-attachments/assets/c555c22c-a5c9-429b-9ae6-c35261132a1b)

  •	You should see sachin.txt.zip listed.

### Step 6: Generate Hash Using zip2john

  •	Execute:
  ![Screenshot 2025-04-24 143148](https://github.com/user-attachments/assets/784e98c5-84f5-4d46-96bd-6a66d79ab858)


### Step 7: Verify the Hash File (Optional)
  •	Open hash.txt to ensure it contains the hash line.
  
![Screenshot 2025-04-24 143222](https://github.com/user-attachments/assets/25159e49-42b4-4485-8219-35afa24631a4)


### Step 8: Start Cracking the Password
  •	Run:
  
 ![Screenshot 2025-04-24 143356](https://github.com/user-attachments/assets/d8cd28ec-0da1-4eff-8f3d-b1687c9f0f96)


## OUTPUT:View the Cracked Password
  • After cracking is complete, reveal the password using:
  

![Screenshot 2025-04-24 143439](https://github.com/user-attachments/assets/58b3b97a-e1bc-45ad-9d38-537e8938a301)


  •	The terminal will display the filename and its cracked password.


## RESULT:
The password hashes were successfully cracked using John the Ripper.
