# Latest Kemendikbud News
this package will get the latest news from Indonesian Ministry of Education and Culture (Kemdikbud)

## How it Work?
This package will scrape from [Kemendikbud](https://kemendikbud.go.id) to get latest news from kemendikbud website
This package will use BeautifulSoup4 and Requests, to produce output in the form of JSON that is ready to be used in web or mobile applications

##How to Use?
```
import beritaterkini

if __name__ == '__main__':
    print('Aplikasi Utama')
    result = beritaterkini.ekstraksi_data()
    beritaterkini.tampilkan_hasil(result)
```

## Author
Irfan Basyar