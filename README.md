# no_as_a_service.cr
Web-API for [naas.isalman.dev](https://naas.isalman.dev/) an tiny API that returns random, generic, creative, and sometimes hilarious rejection reasons - perfectly suited for any scenario: personal, professional, student life, dev life, or just because.

[![Github Card](https://github-readme-stats.vercel.app/api/pin/?theme=transparent&hide_border=true&show_owner=true&username=hotheadhacker&repo=no-as-a-service)](https://github.com/hotheadhacker/no-as-a-service)

## Example
```cr
require "./no_as_a_service"

naas = NoAsAService.new
no = naas.get_no()
puts no
```
