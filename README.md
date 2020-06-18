# Documentation ( Municipio, Posto-Administrativo, Suco, Adeia ) name in Timor Leste

## How to use :

- Get all Municipio : https://api-tl-place.herokuapp.com/api/municipio
- Get all Posto Administrativo : https://api-tl-place.herokuapp.com/api/posto-administrativo
- Get all Sucos : https://api-tl-place.herokuapp.com/api/sucos
- Get all Aldeias : https://api-tl-place.herokuapp.com/api/aldeias

---

- Get all Posto Administrativo based on Municipio : <br />
    URL :  <https://api-tl-place.herokuapp.com/api/municipio/<:idMunicipio>/posto-administrativo> <br />
    Example : https://api-tl-place.herokuapp.com/api/municipio/5eb6b6036f43c107bc95bdf0/posto-administrativo  <br />
- Get all Sucos based on Municipio :  <br />
    URL : https://api-tl-place.herokuapp.com/api/municipio/{:idMunicipio}/sucos <br />
    Example : https://api-tl-place.herokuapp.com/api/municipio/5eb6b6036f43c107bc95bdf0/sucos <br />
- Get all Aldeias based on Municipio : <br />
    URL :  https://api-tl-place.herokuapp.com/api/municipio/{:idMunicipio}/aldeias <br />
    Example : https://api-tl-place.herokuapp.com/api/municipio/5eb6b6036f43c107bc95bdf0/aldeias <br />

---

- Get all Sucos based on Posto Administrativo : https://api-tl-place.herokuapp.com/api/posto-administrativo/:idPostoAdministrativo/sucos
- Get all Aldeias based on Posto Administrativo : https://api-tl-place.herokuapp.com/api/posto-administrativo/:idPostoAdministrativo/sucos

---

- Get all Aldeias based on Sucos : https://api-tl-place.herokuapp.com/api/sucos/:idSuco/aldeias

## Demo : 
 https://demo-get-data-from-api.herokuapp.com

### Reference :

###### Data : http://www.statistics.gov.tl/aldeia-populations/

If uncompleted data please Contact to : pires.joao1995@gmail.com
