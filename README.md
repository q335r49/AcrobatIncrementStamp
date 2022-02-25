### Acrobat Incremental Stamp
Auto-incrementing stamp for Acrobat. 

### Installation
Place `Increment.pdf` in the acrobat stamps folder:
Windows: `C:\Users\*User Name*\AppData\Roaming\Adobe\Acrobat\11.0\Stamps\`
Mac: `/Users/*User Name*/Library/Application Support/Adobe/Acrobat/DC/Stamps/`
(Or find the folder via JavaScript Console with `app.getPath('user','stamps')` + Strg \[or\] Command Enter.)

### Usage
- Stamp will prompt for start value the first time it is used in a document
- Use the second stamp to reset the value
- Increments numerically `1 2 3`, lowercase alphabetic `a b c`, or uppercase alphabetic `A B C`


