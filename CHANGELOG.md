#0.1.9
 - fix exception trace recursive call
 - fix exit on first error
 - fix tests to cope with php unit 8
 - use php7.2 or newer version

#0.2.0
 - rename Reporter to ouch
 - rename on  => enableErrorHandler (makes more sense)
 - rename off => disableErrorHandler (makes more sense)
 - adding a better function for read error file
 - adding support for console errors

#0.3.0
 - fix duplicate html erros
 - fix duplicate cli errors
 - new http error interface
 - adding support for environments (dev, pro)

#0.3.1
 - fix exceptions trace view