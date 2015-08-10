# Address-Falsehoods
A list of falsehoods about addresses

- **All Addresses Have Postal Codes**
  - Ireland would disagree with you (with the exception of Dublin). There are also other [countries without postal codes](https://hellowahab.wordpress.com/2011/05/24/list-of-countries-without-postal-codes/).
- **The Same Address Can't Be In Different Countries**
  - Except the fact [Büsingen](https://en.wikipedia.org/wiki/B%C3%BCsingen_am_Hochrhein#Post_and_telecommunications) is located in the German/Swiss border area.
- **It's perfectly fine to use Zip Code instead of Postal Code**
  - Because Dick Code makes perfect sense. "zip" in Arabic means dick.
- **A person can only have one address**
  - A person can either own multiple properties or a child could have an address with mother, an address with a father, etc.
- **An Address will have a street name**
  - [Japan's addressing system](https://en.wikipedia.org/wiki/Japanese_addressing_system) is pretty complex and most Japanese streets do not have names.
- **Postal codes should be stored in a database using an integer column**
  - Reminds me when I inherited a project that the previous developer did this and then the client sent over data with Massachusetts ZIP Codes which start with 0.
- **Postal codes won't start with a zero**
  - Norway also has postcodes which can start with a 0 (0368 is not the same as 368). **Related:** Postal codes should be stored in a database using an integer column.
- **An address postal code can't contain a space**
  - Sweden has a space after the first digit (5 4367). **Related:** Postal codes should be stored in a database using an integer column.
- **An address will start with, or at least include, a building number.**
  - Counterexample: Royal Opera House, Covent Garden, London, WC2E 9DD, United Kingdom.
- **An address with a building number will be all-numeric.**
  - Counterexample: 1A Egmont Road, Middlesbrough, TS4 2HT
- **An address will not have a building that is numbered zero**
  - Counterexample: 0 Egmont Road, Middlesbrough, TS4 2HT
- **Street numbers (and building numbers) don't contain fractions**
  -  43rd ½ St, Pittsburgh, PA, and of fractional building numbers. These can be written in unicode (43rd ½ St), as a fraction with a slash (43 1/2) or as a decimal (43.5)
- **An address that has a building name won't have a building number (or vice-versa)**
  -  Counterexample: Flat 1.4, Ziggurat Building, 60-66 Saffron Hill, London, EC1N 8QX, United Kingdom
- **A building number will only be used once per street**
  -  Counterexample: The difference between 50 Ammanford Road, Tycroes, Ammanford, SA18 3QJ and 50 Ammanford Road, Llandybie, Ammanford, SA18 3YF is about 4 miles [Google Maps](https://www.google.co.uk/maps?q=SA18+3QJ+to+SA18+3YF).
- **If an address line has a number, it's the building number.**
  -  Don't forget about suite numbers, floor numbers, unit numbers, and organisations with numbers in their names. An address from Japan with fifteen digits in six separate numbers (five if you count the zip code as a single number). The format is: 980-0804 (zip code), Miyagi-ken (prefecture) Sendai-shi (city) Aoba-ku (ward) Kokubuncho (district) 4-10-20 (sub-district-number block-number lot-number) Sendai (building name) 401 (flat number).
- **If the first address line has a number, it must be a building number**
  - Counterexample: 3 Store, 311-318 High Holborn, London, WC1V 7BN 
- **If the addresses on the left of the road are even, the addresses on the right must be odd**
  - [Boulevard Théophile Sueur, Montreuil, Seine-Saint-Denis, France](https://maps.google.fr/maps?q=48.857415,2.467167) has evens-only on both sides. The two sides are also in different cities and Départements. 
- **A building name won't also be a number**
  - Ten Post Office Sq, Boston MA 02109 USA - which is not, reportedly, the same as 10 Post Office Sq, Boston MA 02109 USA. 
- **An address with leading zeros can be omitted**
  - At 101 Alma St, Apartment 001, Palo Alto - where apartments 1 and 001 were on different floors.
- **A street name won't include a number**
  - Counterexample: 8 Seven Gardens Burgh, WOODBRIDGE, IP13 6SU 
- **Street names that have numbers will be expressed as words, not digits**
  - Streets can be numbered in the Netherlands - for example, Plein 1944 in Nijmegen
- **When there's a numbered street and a house number, there will be a separator between them**
  - Counterexample: Gondel 2695, Lelystad, means area Gondel, street 26, number 95
- **Street names always end in descriptors like 'street', 'avenue', 'drive', 'square', 'hill' or 'view'**
  - Counterexample: Piccadilly, London, W1J 9PN
- **A street name will only have one descriptor**
  - Counterexample: 17 Hill Street, London, W1J 5LJ or Avenue Road, Toronto, Ontario.
