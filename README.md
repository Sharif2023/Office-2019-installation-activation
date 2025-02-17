# Office-2019-installation-activation

### Download Office Deployment Tool

```bash
https://www.microsoft.com/en-us/download/details.aspx?id=49117
```

### Download Office 2019

```bash
https://config.office.com/deploymentsettings
```

##### Must select

Office Suite: Office Professional Plus 2019 - Volume License

Language: English (us)

### Create a folder in C:\ named 'Office 2019' and downloaded tool

I've already uploaded folders on github

### Run officedeploymenttool_18324-20194

Set Location on 

```bash
C:\Office 2019
```

(File Will Be Extracted There)

### Run cmd as administrator for the setup

```bash
cd C:\office 2019
setup /configure configuration.xml
```

#### An Alternative way for the setup (Optional)

```bash
Start-Process -FilePath "C:\office 2019\setup.exe" -ArgumentList "/configure configuration.xml" -Wait -NoNewWindow
```

### Turn Off antivirus and Run the cmd from Github

It will activate the license

