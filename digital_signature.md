# digital sign

## generate key
> input keySize
>output private key(sk)  and public key(pk)

``` sh
(sk,pk): = generateKey(keySize)
```

## signature
> input message and sk
> output signature

```sh
  sig := sign(sk,message)
```

## vertiy
> input pk,message,signature
> output true or false
```sh
verify(pk,message,sig)
```