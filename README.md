# Music-Db-Generator
## Overall
You have got a music library and dont know what is in it or need a portable file to know whats in there? Then this is a quick solution!

  Just change these lists to your needs.
  
    acceptedFolders = ['flac', 'low quality', 'other']
    acceptedFiles = [".mp3" , ".opus", ".flac", ".m4a"]

  Besides that the scrip needs a folder structure similar to the following
```markdown
├── <location>
│  ├── flac
│  │  ├── Arist01
│  │  |	├── Album01
│  │  |	| ├──Track01
│  │  |	| ├──Track02
│  │  |	| ├──...
│  │  |	├── Album02
│  │  |	| ├──Track01
│  │  |	| ├──Track02
│  │  |	| ├──...
│  |  ├── Arist02
│  │  |	└── ...
|  |  └──...
│  ├── low quality
│  │  ├── Arist01 #Artists can be the same
│  │  |	├── Album03 #Wouldnt make sence to have the same album in different qulitys but also possible
│  │  |	| ├──Track01
│  │  |	| ├──Track02
│  │  |	| ├──...
│  |  ├── Arist03
│  │  |	└── ...
|  |  └──...
|  └──...
```
## Usage
    python musicDb.py
  Simple as that
