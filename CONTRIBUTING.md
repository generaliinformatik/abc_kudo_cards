# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Guide: new additions  

New additions to this repository are usually only made by the repository owner. Currently we only see additions in the provision of additional cards. The following steps are planned to include them:  

1. Upload the new PDF into the directory `docs/`  
2. Extract the first page of the PDF as PNG image file and resize it to the dimensions 200x263 pixels as file `<name>-front.png`  
3. Upload the PNG image file into the directory `docs/images`  
4. Adjust the README.md so that the image file is displayed and the PDF is offered for direct download (see below).  

The README.md must be adapted as follows. Make sure that a maximum of 4 images are displayed per table row to avoid displaying unwanted breaks in the standard view.  

The following example describes the recording of two lines in which the image is displayed at the top and the link todirect download the  PDF at the bottom.

```
| [![<name>](docs/images/<file>-front.png)](docs/<file>.pdf) | [![<name>](docs/images/<file>-front.png)](docs/<file>.pdf) | [![<name>](docs/images/<file>-front.png)](docs/<file>.pdf) | [![<name>](docs/images/<file>-front.png)](docs/<file>.pdf) |

| [<<name>.pdf](https://github.com/<owner>/<repo>/raw/master/docs/<name>.pdf) | [<<name>.pdf](https://github.com/<owner>/<repo>/raw/master/docs/<name>.pdf) | [<<name>.pdf](https://github.com/<owner>/<repo>/raw/master/docs/<name>.pdf) | [<<name>.pdf](https://github.com/<owner>/<repo>/raw/master/docs/<name>.pdf) |
```
