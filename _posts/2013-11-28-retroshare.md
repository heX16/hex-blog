Разьюзал [RetroShare](http://ru.wikipedia.org/wiki/RetroShare).


[Скачать RetroShare](http://sourceforge.net/projects/retroshare/files/RetroShare/0.5.5b/RetroShare_0.5.5b_6876_setup.exe/download)

Пока что мне нравиться. Децентрализовано, анонимно, [P2P](http://ru.wikipedia.org/wiki/P2P), [F2F](http://ru.wikipedia.org/wiki/F2F). Чаты, голосовое общение, форумы, приватный анонимный имиджборд(sic!), письма, скачка файлов. Но конечно многое нужно допиливать.

Краткая инструкция:
--------------------

При первом запуске оно создает аккаунт, нужно водить мышкой по форме до 20% (оно так генерит рандомный ключ).

Когда запуститься, с лево есть кнопки, нажимаем на первую - "синий человечек и зеленый плюс" и сразу Next.

Там внизу нужно ввести мой сертификат, и в том-же окне вверху скопировать ваш сертификат и скинуть его мне (например на мыло hex1625616(A)gmail.com).

Как узнать что АНБ не слушает?
------------------------------
Тут нужен краткий экскурс в RSA шифрование:

Публичные ключи позволяют шифровать сообщение, но ими нельзя его дешифровать.

Дешифровать может только тот у кого есть приватный ключ. Он создается одновременно с публичным ключом, но его ненужно передавать другим людям.

Таким образом мы обмениваемся своими публичными ключами и все, добро пожаловать в асимметричную криптографию!


Стучитесь:
----------

    -----BEGIN PGP PUBLIC KEY BLOCK-----
    Version: OpenPGP:SDK v0.9
     
    xsBNBFKWI6UBCACvcxSg6Xzs7qfID+rx/0blKYn7LEUrsN5aqL503e9t6u8JkpYX
    MLMHV2g1/1aamjDLmfffS5TcHBF/mBUVABkBxlv9IGA5kfhG0Yw4Dxh9dqVp3GUu
    XNFRsqkvpnGouz/pW3kqvP0q1nX9MlV4itsG2cyrxj5/Ma6PzUTFWoUuZjAQZZu0
    HFTD3V+eWe1i42EUsykVD2YP5smM8L7aOUuJ8+y9m8zun1jla+IxQhsVHOFbYCJ5
    LtSkrrAa8Qwz6Og1tKtdim4NrQzlBDgb6ed8Zht1RfDs2gvjiXM5D5YiwE2mlScA
    DBQ7SUppu4fqYEXjhUsmy8SEesvotpv8wPj3ABEBAAHNImhlWG9yIChHZW5lcmF0
    ZWQgYnkgUmV0cm9TaGFyZSkgPD7CwF8EEwECABMFAlKWI6UJEIsCQwR9yWIoAhkB
    AAD/OAf/RYmmzMjCj3wfDTiXY+GPb+xkUbcjLkUEhVyBRV+ANxAd3KsN/+9F5IYW
    hzcg8vIWhzsERUQ7qOBmgCA8An3fbi1pS9TPMPA7q0gH6YzaEZeT07ghhouv2g0C
    BwBRshQ+Gt+1Q5S0zxqVsFFfh9XNw7M8MCiYmitjit8I5kJHNUjQrubbR5YtAFBv
    BJZaSB1T3Qy3ZHcUTiZtJ0oHHCmPKg/CmPS/yp91wSArNdRUo1EhFAksXx+KUSu0
    4+w1hoKGkzBVDGA1Juo+cYeuOrH03NwvbwRArOe9lH3/dqRPUldO7jzyVu5AlniV
    qaZowC3o77XNh3S2h0sFYHDE4gN2mg==
    =12mQ
    -----END PGP PUBLIC KEY BLOCK-----

