# simple-pdf-cert

Simple PDF Cert creator for NodeJS.

## Sample Code:

```js
const sampleData = {
  logo: {
    path: "./sampleLogo.png",
  },
  company: {
    name: "Idemy Courses Inc",
  },
  words: {
    title: "Certificate of Completion",
    h2: "Awarded To",
    awardee: "User Admin",
    reason: "for completing THE NOTHING course",
  },
};

simplePDFCert(sampleData, "output.pdf");
```

## Screenshot:  

![Screenshot](screenshot.png)

##### ![SamplePDF](test.pdf)