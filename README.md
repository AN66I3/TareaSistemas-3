# TareaSistemas-3
## Primitive Datatype
## Task 1
### Use “Get-Help” to find out more information about 5
cmdlets.
As an example you can use “Get-Service” or “Out-GridView”
Notes:
Get-Help Get-Help
Get-Help New-Item
Get-Help Get-Alias
Get-Help Get-AuthenticodeSignature
Get-Help Get-ControlPanelItem

![EJERCICIO31 1](https://user-images.githubusercontent.com/91564729/160583294-2ad54a38-2aad-4849-9111-43787f2449e3.JPG)
![EJERCICIO-3-1 2](https://user-images.githubusercontent.com/91564729/160583297-ff26cb0c-ac04-40ad-954f-56e32287ec5e.JPG)
![EJERCICIO-3-1 3](https://user-images.githubusercontent.com/91564729/160583301-849fff63-dff6-422f-b6b9-909d4b5b8e84.JPG)
![EJERCICIO-3-1 4](https://user-images.githubusercontent.com/91564729/160583204-86944cd5-3153-4eca-888a-3565ee73092d.JPG)
![EJERCICIO-3-1 5](https://user-images.githubusercontent.com/91564729/160583212-8706c8c6-0c4b-44c8-894f-89b234d25928.JPG)

## Task 2
### Use “Get-Help” with the “–Example” parameter for the
### 5 cmdlets you discovered more about in task 1.
Notes:
Get-Help Get-Help -Examples
Get-Help New-Item -Examples
Get-Help Get-Alias -Examples
Get-Help Get-AuthenticodeSignature -Examples
Get-Help Get-ControlPanelItem -Examples


## Task 3
### Create a new text file named “TestFile.txt” under C:\
Maximo\PowerShell\Workshop1\%USERNAME%
### The cmdlet to make a file and a new directory starts with “New”
Notes:
New-Item -Path C:\ -Name Expo -ItemType Directory
New-Item -Path C:\Sudoblark -Name PowerShell -ItemType Directory
New-Item -Path C:\Sudoblark\PowerShell -Name Workshop1 -ItemType Directory
New-Item -Path C:\Sudoblark\PowerShell\Workshop1 -Name bclark -ItemType Directory
New-Item -Path C:\Sudoblark\PowerShell\Workshop1\bclark\ -Name Testfile.txt -ItemType File


![EJERCICIO-3-3 1](https://user-images.githubusercontent.com/91564729/160583217-ba59de88-6992-49d0-9ea0-32790cf07986.JPG)
![EJERCICIO-3-3 2](https://user-images.githubusercontent.com/91564729/160583220-33303547-7dd9-4c0c-b3eb-ac9f1f8c9ce5.JPG)
![EJERCICIO-3-3 3](https://user-images.githubusercontent.com/91564729/160583223-89d7185b-cc74-4f76-9b7f-429346182245.JPG)
![EJERCICIO-3-3 4](https://user-images.githubusercontent.com/91564729/160583228-d5dea15e-b5a3-46e6-b588-3d35cefb5f44.JPG)
![EJERCICIO-3-3 5](https://user-images.githubusercontent.com/91564729/160583234-3b7aabf4-3851-44cb-9555-9142f0dd6dbd.JPG)

## Task 4
### Populate the text file you created in task 3 with all
three datatypes we’ve covered: “Boolean”, “String”
and “Int”
### The cmdlet you need starts with “Add”
Notes:
Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value True
Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Hello"
Add-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value 42


![EJERCICIO-3-4](https://user-images.githubusercontent.com/91564729/160583237-46962f25-ee31-4d7c-934f-6a2bedb62862.JPG)

## Task 5
## The cmdlet you need to read data from the text file begins to “Get”
Notes:
Get-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt | Get-Member
![EJERCICIO-3-5](https://user-images.githubusercontent.com/91564729/160583245-f7a57378-bf02-4535-a598-14bd4d3faef2.JPG)

## Task 6
Notes:
Set-Content -Path C:\Sudoblark\PowerShell\Workshop1\bclark\Testfile.txt -Value "Boooooo"
![EJERCICIO-3-6](https://user-images.githubusercontent.com/91564729/160583252-8087bd0c-0191-45f0-9535-4da1c67a2ba1.JPG)

## Task7
![EJERCICIO-3-7](https://user-images.githubusercontent.com/91564729/160583257-8a64942d-c924-4ce7-9f15-e2505171936d.JPG)

## Task8
![EJERCICIO-3-8](https://user-images.githubusercontent.com/91564729/160583270-ddd78c6f-56c5-4d77-971f-be33a37853cc.JPG)

## Task9
![EJERCICIO-3-9 1](https://user-images.githubusercontent.com/91564729/160583273-f90960fb-0af6-4ab7-9455-39c44c738653.JPG)
![EJERCICIO-3-9 2](https://user-images.githubusercontent.com/91564729/160583277-4c1a9146-3d75-47e1-a157-dc7302195e4e.JPG)
![EJERCICIO-3-9 3](https://user-images.githubusercontent.com/91564729/160583281-e774cc6d-f139-4e81-b7af-04286ef6f302.JPG)
![EJERCICIO-3-9 4](https://user-images.githubusercontent.com/91564729/160583283-eafd88e3-abcc-496c-8e7d-ca5618423b27.JPG)
![EJERCICIO-3-9 5](https://user-images.githubusercontent.com/91564729/160583291-0236228f-25ec-4417-97ec-cb631a78a165.JPG)

