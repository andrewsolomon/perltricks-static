{
   "tags" : [
      "configuration",
      "cpan",
      "module",
      "operator",
      "old_site"
   ],
   "image" : null,
   "title" : "How to install a specific version of a Perl module with CPAN",
   "authors" : [
      "David Farrell"
   ],
   "description" : "",
   "slug" : "4/2013/3/27/How-to-install-a-specific-version-of-a-Perl-module-with-CPAN",
   "date" : "2013-03-27T23:32:57",
   "draft" : false
}

Perl modules are usually installed via CPAN on the command line. This is invoked with the following syntax:

``` prettyprint
cpan My::Module
```

CPAN will always try to install the latest stable version of a module, which is a sensible default, however this may not always be the required behaviour. To have CPAN install a specific version of a module, you need to provide the full module distribution filename including the author. For example to install the module Set::Object version 1.28, at the command line type:

``` prettyprint
cpan SAMV/Set-Object-1.28.tar.gz
```

You can find the distribution filename for a module by searching for the module on [CPAN](http://search.cpan.org/).

