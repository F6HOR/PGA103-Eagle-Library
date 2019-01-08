# PGA103-Eagle-Library
Eagle library for PGA-103 and PGA-103+ component (SOT-89 package).
Tested on Eagle-7.2 and Eagle-7.7.

## Installation
### Linux
* `git clone https://github.com/handiko/PGA103-Eagle-Library.git`
* `cd PGA103-Eagle-Library`
* Copy the `pga103.lbr` into your Eagle library folder. For example, if your eagle library folder is located in `/opt/eagle-7.2.0/lbr`, then type: `sudo cp pga103.lbr /opt/eagle-7.2.0/lbr`
* Open the Eagle CAD, then **Library ---> Use All**
* Now the pga103.lbr should be listed in your Eagle library.

### Windows
* Download as zip
* Unzip
* copy the `pga103.lbr` into your Eagle library folder, for example : **C:\EAGLE-7.2.0\lbr**
* Open the Eagle CAD, then **Library --> Use All**

## Example
From **PGA103-Eagle-Library/Example/Simple-LNA** folder
![alt text](https://github.com/handiko/PGA103-Eagle-Library/blob/master/Pics/Simple-LNA-sch.png)
![alt text](https://github.com/handiko/PGA103-Eagle-Library/blob/master/Pics/Simple-LNA-brd.png)

## TODO
* Make PGA-103 symbol a little bit nicer
* Make a better example sch / board
* Adding description to the Device
* Better documentation / README
* ...

## Contributing
1. Fork it (https://github.com/handiko/PGA103-Eagle-Library/fork)
2. Create new branch (`git checkout -b add-blah-blah`)
3. Do some editing / create new feature
4. Commit your works (`git commit -m "Adding some blah blah blah.."`)
5. Push to the branch (`git push -u origin add-blah-blah`)
6. Create a new Pull Request
