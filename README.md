# python_tools
Main repository for all relevant ScholarTools functionality.
For information about any specific repository, click on the folder above to be taken to that repository.

## Downloading the Tools
### Downloading all respositories
In order to download all submodules, run the following command:  
`git clone --recurse-submodules https://github.com/ScholarTools/python_tools ScholarTools`

Alternately, the following commands:    
`git clone https://github.com/ScholarTools/python_tools ScholarTools`  
`cd ScholarTools`  
`git submodule update --init --recursive`


### Downloading individual repositories
First, clone this repo to get the file structure in place:  
`git clone https://github.com/ScholarTools/python_tools ScholarTools`  
`cd ScholarTools`

Then, for each submodule you would like to download, run:  
`git submodule update --init -- [submodule_name]`

