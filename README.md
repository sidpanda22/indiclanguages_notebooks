Wkipedia dumps:
The following languages' articles are taken:
languages = { "hindi":"hi",
             "bengali":"bn",
             "urdu":"ur",
             "malayalam":"ml",
             "tamil":"ta",
             "marathi":"mr",
             "telugu":"te",
             "kannada":"kn",
             "burmese":"my",
             "punjabi":"pa",
             "assamese":'as',
             "nepali":'ne',
             'sanskrit':'sa',
             'western_punjabi':'pnb',
             'gujrati':'gu',
             'odia':'or',
             'bhojpuri':'bh',
             'santali':'sat',
             'sindhi':'sd',
             'fiji_hindi':'hif',
             'maithili':'mai',
             'tulu':'tcy',
             'tibetan':'bo',
             'bushnupriya_manipuri':'bpy',
             'kashmiri':'ks',
             'awadhi':'awa',
             'konkani':'gom',
             }
Data format:
    Dict[lang_id]
        Dataset({
            features: ['id', 'url', 'title', 'text'],
            num_rows: 160068
        })
            Each dataset has each row as a dict:
                {'id':, 'url':'', 'title':'', 'text':''}