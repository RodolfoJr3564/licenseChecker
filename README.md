# License checker

The purpose of this Script is to parse a JSON or CSV file, list the licenses and filter data according to the license. Writing the extracted data to a new file or displaying it on screen.

To extract the licenses, the [package-license-extracto](https://github.com/smaro-nitr/package-license-extractor), which generates a list of licenses in JSON or CSV format.

Accepts input from Json or CSV files.

### How to use

#### Extract the licenses

Add the dependency [package-license-extracto](https://github.com/smaro-nitr/package-license-extractor).

```shell
npm install package-license-extractor
```

In the main folder of the project, run the command

```shell
npx extract-license
```

then it will create a folder called `extracted_license` and inside it there will be a JSON file and another CSV file with the data.

#### Run the interface

Now just run

```shell
npm run execute		|| 		node index.js
```

And add the file path with the extension, without quotes.

> ex:  path/file.json



### To do:

- [x] Read CSV functionality.

- [x] Read JSON functionality.

- [x] Write analysis result in CSV .

- [x] Write analysis result in JSON .

- [ ] Find another library ready to convert CSV values

- [ ] Pass code to typescript to apply OOP

  