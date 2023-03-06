# NAS Device

[![made-with badge](https://img.shields.io/static/v1?label=Made%20with&message=Obsidian&color=7d5bed&logo=obsidian&labelColor=1a1a1a&style=flat)](https://obsidian.md/)

[![type](https://img.shields.io/static/v1?label=Type&message=documentation&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAi0lEQVRIS+2WMQ7AIAhF/UNXrtP7rz2OYxeqTWxMTBUSxQVXfnzyQQKC8YExL7zAGCNbgIkIsIKVhBw4vbR7unR6Gp0LvwxXd2v+EvkdDpxWXpWlRTyi9/pABRyBJHEHSlxSadxSlV0SsVsqcUml2W/pynWxnsXNisHMRxrCl8qvH3ECnQDuOmy+0zwB4WNxmUKgwwAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/documentation/) [![category](https://img.shields.io/static/v1?label=Category&message=network-and-servers&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAB9UlEQVRIS6VWMU7DQBDkDAQEdrAoCISCAomCL1DxC95Azy9oeQS/oOIHVFAgREFoCHGCRSzZzEU+63LZ9W6CO/vudmZ2d9Zn1pTPaDSqut2usduHw+FpFEUv7t1fk8LNAkiPDWj3+ADuTPjNvXMxWwGzLCuqqtqwh5MkiY0xEwfOAfrEKFAWUBO4DZQDXgCEqjuouvbZUanUrocpngMMVUkKtKC+WhFQUudAUd8r1PkepJ/w7Tysn4uzkNJlascF9WOASAki6w0xrn19b3Gpps5y3kRfJADPZgr9gJSP0EgDHDiQ/Mp50PfxAmDtuQhsZmb/z0OVhwSkmGrSGp5bGRDp3EFaJ5JaiahdZ2vYNj/JkWVMgW7sgNw2yOW+99gacp7TeFE72OcUrgo4Ho93+/3+D5T9QmGHm0BNSnHgMI7jj9Ai2tElZGCK9S3S+GA4BcNNydBaIuEstu/iLJWCa+pLDm+Nz+xQAsBenucnRVG8asFq0s/Yf9YoVAI21wyn3N4I7M1A8ijWHwB42XrFqIO9YfMRlVqqyXC5ukED3nIEVJcoBXv1lmWa5gIpeeQioyTWVj1uXf0DpgKUZbmfpunXKnVnU9rWDKiTHRSDNkDu36iqIQK/Q+mxU8sBYniL/1EVoJ9Wqwo/5x6Cf9YKv6Em1XbNH5bGfSwvuRe1AAAAAElFTkSuQmCC&labelColor=1a1a1a&style=flat)](https://pabloagn.com/categories/network-and-servers/) [![technologies](https://img.shields.io/static/v1?label=Technologies&message=X&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAACXBIWXMAAAsTAAALEwEAmpwYAAAA1klEQVR4nM2RMW7CUBBEnUikIQUIlBJxrrQgJG7ABRBnoUkaWhpoUgWJlgNYbvz/G1dUi1ayoy87rpOtVrszs6OdLPtXlef5UNJXjHHcCwohjMzsKZ3FGN+Bq/e+c0xHGfiWtEznkg6SNnW/dIxjs0YJ2AMnM3tJSFPgHkKY17gBcAQ+zOw5A3aSbsCkdW0NnNOZY2rstpcInJ3cS/SzwGdqtSzLmdusquqtIXWsehVF8QpcJK1qmxt/TMv6wjE/z0leP27i8Ag8inT/axxtAQ+9o/zn9QD3JOiyTjnQEQAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/technologies/)

- A **NAS device** (_Network Attached Storage_) is a file-level computer data storage server connected to a computer network providing data access to a heterogeneous group of clients.
- Once a NAS is connected to a computer network, it can be accessed by using multiple protocols and clients.
- WinSCP is a prefered client for file transfer due to the easy-to-use GUI, and multiple customization options.
- We can also directly use _ssh_, but this is out of this document's scope and is covered on its respective Documentation.

# 1. Connect to a QNAP NAS

### 1.1 Connect to QNAP NAS via WinSCP
- We can connect to a _QNAP NAS_ via WinSCP using `SFTP`:
1. Connect to main network (main modem or main router) configured with QNAP NAS.
2. Open Qfinder Pro.
3. Look for IP Address of QNAP NAS.
4. Start a new session on WinSCP.
5. Input the following parameters:
	- File Protocol: `SFTP`
	- Host Name: `IP Address from QNAP NAS`
	- Port Number: `22`
	- User name: `admin`
	- Password: `admin password`
6. Login

### 3.2 Transfer Files
- To transfer a file, simply **right-click copy** on source and **right-click paste** on target.
- Some considerations:
	- Simply dragging a file / folder will not move it and will instead copy from source to target.
	- On QNAP NAS, a file transfer from Windows Local Machine to NAS will result in a file / folder with the following permissions:
		- `644 (rw-r--r--)`
	- Transfer speed for an `.mkv` file is about 50 MB/s

### 3.3 External Storage & Mount Points
- Whenever we include a new external drive into the NAS, we will be able to format it, create Storage Pools and create Data Volumes. 
- Upon creating a new Storage Pool and subsequent Data Volume in QNAP, the system will create a new mountpoint located on `/share/` by default. Whenever the device boots up, Data Volumes will be mounted on their respective mountpoints.

### 3.4 Folder Types
- _Folders_ in a NAS can be divided into two groups:
	- Folders cannot be accessed remotely over the Network.
	- Shared Folders can be accessed remotely over Network if the NAS is connected.

#### 3.4.1 Conventional Folders
- _Conventional Folders_ cannot be accessed remotely over the Network.

#### 3.4.2 Shared Folders
- _Shared Folders_ can be accessed remotely over Network if the NAS is connected to a Network.
- If we have access to a _Shared Folder_, we have access to all the Folders within that _Shared Folder_ as well.

### 3.5 Creating New Shared Folders Via QNAP NAS Admin Web Interface
- We can create a new _Shared Folder_ by following the steps below:
1. Head to **File Station**.
2. Select the **Data Volume** where you wish your folder to be created on.
3. Click on the three dots following the **Volume Name**.
4. Select **Create a Shared Folder**.
5. Define a **Folder Name** (will be used to access the folder using `/path/foldername`)
6. Define an optional **Comment**.
7. If we chose the wrong Data Volume, we can change it by selecting another available **Disk Volume**.
8. We can either **Specify path automatically** (defaults to `/share`, or **Enter path manually**).
9. We can define a **Folder Encryption** mechanism.
10. Click on **Next**.
11. We can set permissions as we require:
	- `RO`: Read Only
	- `RW`: Read/Write
	- `Deny`: Deny access
12. Click **Next**
13. We can define **Guest Access Right** (same options available as above).
	- **WARNING:** Setting any option other than `Deny Access` will result in any guest with a guest account having the possibility to access the Shared Folder **without** an admin password required.
14. Select / unselect all other required options.
15. Click **Finish**.

- The folder has been created and is ready to be used. We can confirm this by logging into a WinSCP session and heading to the folder path. 
- The folder will have the following characteristics (this will of course depend on the options you previously selected):
		- Permission: `777 (rwxrwxrwx)`
			- `r`: Read
			- `w`: Write
			- `x`: Execute
			- File Owner / File Group / All Other Users
	- Owner: `admin`
	- Group: `administrators`

### 3.6 Removing an Existing Shared Folders Via QNAP NAS Admin Web Interface
- Folders cannot be removed directly from the **File Station** interface.
- To delete a Shared Folder (given you have the permissions to do so), we follow the steps below:
1. Open **Control Panel**.
2. Head to **Privilege** and select **Shared Folders**.
3. Select the **Folder** you'd like to remove.
4. Click on **Remove**.
5. Click on **Also delete the data** if you wish to do so.

- The folder is now deleted from the File System.

### 3.7 Personal Setup in QNAP NAS
#### 3.7.1 Data Volumes
- I currently have 2 Data Volumes set up:
	- `DataVol1`:
		- Uses 6 Seagate Ironwolf Pro 8TB External Hard Drives.
		- Is partitioned as RAID 5, and is named RAID Group 1.
		- Is used for bulk storage.
	- `DataVol2`:
		- Uses 2 PCIe M.2 SSD 500GB External Solid State Drives.
		- Is partitioned as RAID 1, and is named RAID Group 2.
		- Is used for application installations and Plex / Roon Server metadata storage.

#### 3.7.2 Folder Structure
##### **Academic**
- Description:
Anything related to academic studies in Bachelors Degree, Masters Degree and Doctorate Degree.

- Located on:
`/share/CACHEDEV1_DATA/Academic/`

- Contains:
`Bachelors Degree`
`Biomass_Project`
`Courses`
`Organic Chemistry`
`Postgraduate Studies`
`Programming`
`Universidad Iberoamericana`

##### **Media**
- Description:
Multimedia such as movies collection, series collection, wallpaper collection, photos collection and old spotify playlists.

- Located on:
`/share/CACHEDEV1_DATA/Media/`

- Contains:
`Art`
`Collections`
`Movies Collection`
`Music`
`Photography`
`Pictures & Videos`
`Playlists`
`Series Collection`
`Server Backups`
`Server Pendings`
`Videos`

##### **Metadata**
- Description:
Multimedia such as movies collection, series collection, wallpaper collection, photos collection and old spotify playlists.

- Located on:
`/share/CACHEDEV1_DATA/Metadata/`

- Contains:
`Databases`
`media.bak`
`Plex_Transcoding`
`RoonServer`

##### **Personal**
- Description:
Personal documents and files.

- Located on:
`/share/CACHEDEV1_DATA/Personal/`

- Contains:
`Compras`
`Important Documents`
`Lentes Graduados`
`Others`
`Pendings`
`Projects`
`System`
`Travel`

##### **Professional**
- Description:
Work-related documents and files.

- Located on:
`/share/CACHEDEV1_DATA/Professional/`

- Contains:
`Bolsa de Trabajo 2018`
`BUNGE`
`CV`
`IFF`
`NIELSENIQ`
`Professional Photoshoot`
`TOEFL iBT`





