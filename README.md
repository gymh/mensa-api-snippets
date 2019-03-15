# mensa-api-snippets

in this repo you will find http calls for gymhmensa-api for different languages

they have been build by the [Postman](https://www.getpostman.com/) code generator and are all based off this request originally created in [Insomnia](https://insomnia.rest/)
```
curl --request POST \
  --url 'https://mensadigital.de/LOGINPLAN.ASPX?P=FO111&E=herz' \
  --form __VIEWSTATE=/wEPDwUJODQ5MDQ3NzI3D2QWAmYPZBYEAgEPDxYCHgRUZXh0BQVGTzExMWRkAgIPDxYCHwAFBGhlcnpkZGS0fKrirWn0k/UdgWunNZPR8jF3ShBdJIWVB0yGj1GA2w== \
  --form __VIEWSTATEGENERATOR=D5B5CA0F \
  --form btnLogin=
```

## available languages
- [http](http.codesnippet)
- [c-lib-curl](c-lib-curl.codesnippet)
- [curl](curl.codesnippet)
- [c#-RestSharp](c#-RestSharp.codesnippet)
- [go](go.codesnippet)
- [java-okhttp](java-okhttp.codesnippet)
- [js-jquery-ajax](js-jquery-ajax.codesnippet)
- [js-xhr](js-xhr.codesnippet)
- [nodejs-request](nodejs-request.codesnippet)
- [python-request](python-request.codesnippet)
- [Ruby-Net-Http](Ruby-Net-Http.codesnippet)

## other languages
if you need other languages, simply import the raw curl request on the top into Postman or Insomnia (https://www.google.com/search?q=insomnia+import+curl).