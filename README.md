# agile-upfront-modules
Modules for the UpFront farmework

# Example

Do the following to test the default upfront example with this storage module:

```
git clone https://github.com/SEDARI/UPFROnt/
git clone https://github.com/Agile-IoT/agile-upfront-leveldb
cd UPFROnt
npm install --save https://github.com/Agile-IoT/agile-upfront-leveldb
mv ../agile-upfront-leveldb/example/settings.js ./example/online/settings.js
npm install
cd ./example/online/
node index.js
```
