# Parsed Minneapolis City Directory Entries

### Contents

Parsed entries from pages 104-108 of the [1900 Minneapolis City Directory](https://box2.nmtvault.com/Hennepin2/jsp/RcWebImageViewer.jsp?doc_id=7083e412-1de2-42fe-b070-7f82e5c869a4/mnmhcl00/20130429/00000008). Each file contains structured data that has been processed using an OCR pipeline involving OpenCV2, scikit-image, regex, PaddleOCR and Tesseract.

The data is in the following format:

```json
{  
  "FirstName": "Emma",  
  "LastName": "Abt",  
  "Spouse": "Michael",  
  "Occupation": "tchr",  
  "CompanyName": null,  
  "HomeAddress": {  
    "StreetNumber": "2309",  
    "StreetName": "Bryant av s",  
    "ApartmentOrUnit": null,  
    "ResidenceIndicator": "boards"  
  },  
  "WorkAddress": null,  
  "Telephone": null,  
  "DirectoryName": "Minneapolis 1900",  
  "PageNumber": 106  
}
```
