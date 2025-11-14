# no_as_a_service.cr
Web-API for [naas.isalman.dev](https://naas.isalman.dev/) an tiny API that returns random, generic, creative, and sometimes hilarious rejection reasons - perfectly suited for any scenario: personal, professional, student life, dev life, or just because.
[GitHub](https://github.com/hotheadhacker/no-as-a-service)

## Example
```cr
require "./ip_stack"

naas = NoAsAService.new
no = naas.get_no()
puts no
```
