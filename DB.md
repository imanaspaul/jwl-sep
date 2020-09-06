Database design for jwellery website

### Product
- ID( UUID )
- name( string )
- price( float )
- offer_price( float )
- product description( string )


### Product details
- product( fk )
- height( float )
- width( float )
- thikness( float )


### Metal details
- product( fk )
- Metal ( string )
- purity ( string )
- metal weight (  float )


### details
- product ( fk )
- name ( string )
- details ( richtext )


### varient
- ID ( UUID )
- Name ( string )
- product ( fk )


### Product varient
- varient ( fk )
- style_num ( string )
- name ( string )
- value ( string )
- image ( image )
- price ( float )
- offer_price( float )
- short description ( string )


### Ratings
- ID ( UUID )
- product ( fk )
- user ( fk )
- title ( string )
- review ( string )
- rating ( integer )