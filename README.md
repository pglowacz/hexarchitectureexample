# hexarchitectureexample

Struktura katalogów

```
..domain (technological transparent)
  ..user
  ..product
  ..order
  ..log
  ..api(incoming i.e for interfaces that are used as ports in rest controllers)
  ..spi(outgoing i.e for interfaces that are used as ports for access to db/rest template etc.)
  ..xxx
..infrastructure(adapters that uses domain)
  ..adapter-rest
    ..services (implementation of api)
  ..adapter-jpa
    ..services (implementation of spi)
  ..adapter-xxx
   ```
