# Mari Belajar Markdown from Scratch
Oleh Anonymous van Sukabumi  
10 November 2024
***

>Teks markdown ini masih dalam pengembangan dan akan diperbarui secara berkala*
>>note * : Maksudnya berkala apabila penulis nya lagi niat** update
>>> note ** : Niat bisa datang dan hilang secara tiba-tiba
>>>> Quote ini sudah beranak pinak sampai 4 tumpuk.

Berikut adalah hal-hal dasar yang perlu diketahui dalam membuat sebuah teks berformat *markdown* (.md)


## List Pelajaran
1. ### Heading
2. ### Heading Alternate
3. ### Paragraph: 
    1. More paragraph using 1 blank line
    1. More text line using 2 blank space
    1. Line break use \ or 2 whitespace
    1. Do not add 'tab' on new paragraph
    1. Maintain text always left-aligned
    
4. ### Emphasis: 
    1. Bold use ** Text **

        > Example: **Ini teks pakai bintang-bintang**

    1. Strong use __ Text __
    1. Italic use  * Text *
    1. Bold Italic use *** Text ***

5.  ### Quote: 
    1. Single Blockquotes use >
    1. Nested Blockquotes use >>>

6. ### Lists:
    + Ordered Lists should startwith number one
    + Numbering should written with dot (.)
    + Un-ordered Lists should use (-), (*), (=)
        + Indentation for making nest lists
        + *This is example of indentation*
            + *This is example 1*
            * *This is example 2*
7. ### Elements inside Lists:
    1. Add paragraph

        Use 4 whitespace and 1 blank line to create this caption of certiain list.\
        The list still continue no matter what you put in this caption.  

    1. Add quote

        > To add 'Blockquotes' as a cpation of the list, just simply as put delimiter > at teh beginning of caption. Still it should go with 4 whitespaces and 1 blank line to separate the list and caption.

    1. Code blocks

        To add 'Code' inside your lists. Feel free to write down the code without any mandatory delimiter. It will go with 8 whitespace and 1 blank line. Just like this, we put a HTML code

        Never forget always put 8 whitespace while adding any code 

            <html>
                <head>
                    <meta charset="UTF-8">
                    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                    <meta name="description" content="Ini adalah website bisnis latihan"/>
                    <link rel="stylesheet" href="style.css" />
                    <title>Web Bisnis</title>
                </head>

                <style>
                    .header {
                        overflow: hidden;
                        background-color: #c9d3ff;
                        padding: 10px 10px;
                    }


                    .header a {
                        float: left;
                        color: rgb(30, 32, 110);
                        text-align: center;
                        padding: 10px;
                        text-decoration: none;
                        font-size: 18px;
                        line-height: 25px;
                        border-radius: 5px;
                    }
                </style>

                <body>
                    <title>Test 123</title>
                </body>
            </html>

    1. Images

        Use delimiter (!) to insert an images. 
            
        ![Pic, Adorable Kitsune Yae Miko](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/7dfc1495-12d2-4c9a-9ebe-96eefc3d9164/dfi2rgr-f93f00d7-8880-4004-bb32-a7fd3b6e5b0c.png/v1/fill/w_1280,h_1280,q_80,strp/yae_miko_kitsune_form_by_adartsonx_dfi2rgr-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTI4MCIsInBhdGgiOiJcL2ZcLzdkZmMxNDk1LTEyZDItNGM5YS05ZWJlLTk2ZWVmYzNkOTE2NFwvZGZpMnJnci1mOTNmMDBkNy04ODgwLTQwMDQtYmIzMi1hN2ZkM2I2ZTViMGMucG5nIiwid2lkdGgiOiI8PTEyODAifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.-2AwNa_Ghf7w0lNZaU7wvqtoiAYUGZCZq-bftpVyKG8)

8. ### Code
    
    Sebaiknya gunakan delimiter (`) saat membuat teks berjenis ``kode``. Menulis code tanpa delimiter tetap bisa dilakukan

    Contoh kode langsung (code-block)

        sudo apt-get upgrade

    Contoh kode dengan delimiter (`)

    `sudo apt-get upgrade`

9. ### Links

    Untuk membuat link/tautan gunakan sytax ini  
    
   >`[Nama Tampilan](URL)`  
    >`[Google Scholar](https://scholar.google.com/)`

    Maka akan tampil seperti ini 
    
   > [Google Scholar](https://scholar.google.com/)

    Website favorit saya adalah [Google Translate](https://translate/google.com) karena sangat membantu pekerjaan saya sebagai petani.


Sumber:
<https://www.markdownguide.org/basic-syntax/>