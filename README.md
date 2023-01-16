# AnyActive : URL Classifier based on HTTPcodes<p>
Simple python tool to classify bulk amount of urls based on httpcodes.

## <b> Features </b>
- in single url mode displays response header information 
- in list mode classifies each item from list and save to a particular file 
- can specify to which directory files should be saved under
## <b> Installing </b>
#### 1. Clone repository:
```
$ git clone https://github.com/callmelokzy/anyactive
$ cd anyactive
```
#### 2. Install the dependencies:
```
$ pip3 install -r requirements.txt
```


## <b> Usage </b>

#### Help
```
$ python3 anyactive.py -h/--help
```
#### For List of URLs:
```
$ python3 anyactive.py -l "path to the file containing urls/suddoamins" -d "path to save files"
```
- sample
- ![image](https://user-images.githubusercontent.com/56486732/212759227-c6c132e7-c549-47fa-a757-304306b75bd0.png)

#### For single URL: 
```
$ python3 anyactive.py -u "url to check"
```
- sample  </sub>
- ![image](https://user-images.githubusercontent.com/56486732/212749669-9b78d2b3-4212-43b0-a590-901090184d55.png)




#### Credits: 
