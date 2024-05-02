# Nesting
talabalar = {
    '1-kurs': {
        'ismi' : 'Ali',
        'familiyasi' : 'Yo\'ldashev',
        'yili' : 2001,
        'yo\'nalishi' : 'Iqdisodiyot'
    },
     
    '2-kurs' : {
        'ismi' : 'Alisher',
        'familiyasi' : 'Nosirov',
        'yili' : 2000,
        'yo\'nalishi' : 'Doktarantura'
    },
    
    '3-kurs' : {
        'ismi'  : 'Ahror',
        'familiyasi' : 'Nasimov',
        'yili' : 1999,
        'yo\'nalishi' : 'Magestratura'
    }

}


for key, value in talabalar.items():
    print(f' \n      {key}')
    for value1, value2 in value.items():
        print(f'{value1.capitalize()}: {value2}')
