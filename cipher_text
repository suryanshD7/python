alphabet = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z',
            'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']


direction = input('Type "encode" to encrypt, type "decode" to decrypt: ').lower()
text = input('Type your message: ').lower()
shift = int(input('Type the shift number: '))


def encrypt(plain_text,shift_count):
    cipher_text = ''
    for i in text:
        orignal_place = alphabet.index(i)
        new_place = orignal_place + shift
        cipher_text += alphabet[new_place]
    print(cipher_text)


def decrypt(cipher_text,shift_count):
    plain_text = ''
    for i in text:
        orignal_place = alphabet.index(i)
        new_place = orignal_place - shift
        plain_text += alphabet[new_place]
    print(plain_text)


if direction == 'encode':
    encrypt(plain_text = text,shift_count = shift)
elif direction == 'decode':
    decrypt(cipher_text = text,shift_count = shift)
else:
    print('Select either encode or decode! ')
