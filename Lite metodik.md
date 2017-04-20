**BIM**  
*Workshop kring BIM i Ledamotshuset*

Målet med denna workshop kring BIM i Ledamotshuset är att precisera vilka
BIM-nyttor som skall användas i projektet och hur leveranser av dessa skall ske
till olika delar av er organisation så att de kommer utföras med rätt
information till rätt plats i rätt tid.

För att kunna kravställa BIM-nyttor i projektet behöver vi efter utförd workshop
ha en bra grund att stå på för att svara på frågor som:

-   Vem som efterfrågar vilken typ av information

-   Hur de vill använda informationen

-   I vilken format informationen skall levereras för kunna tas emot

-   Exakt vilket innehåll som krävs och hur det skall vara formaterat

-   När informationen behöver levereras i projektets tidplan

Detta beskrivs övergripande i ert ramverk *BIM i state*n (Bild 3: Införandet av
BIM ur ett nyttoperspektiv ur ”Strategi för BIM i förvaltning och projekt”,
2014-05-23 s. 8).

![](media/64a16bf224c5ad6d55e676e63f2cf2c0.png)

För att få utväxling av BIM-nyttor i projektet är det viktigt att förstå exakt
hur de ska tillämpas och att drivkraften bakom dem kommer från verksamhetens
mål. BIM i staten utgår från två typer av processer som driver
informationsbehovet. För att inte information skall gå förlorad i projektet är
det viktigt att RDF är delaktig i både projekt- och förvaltningsprocesser så att
dessa kan samordnas med en tydlig och säker informationsöverföring.

De nyttor som vi inför denna workshop identifierat fokuserar på vinster som kan
uppnås genom att RDF, på ett tydligt och engagerande sätt, är delaktiga i olika
arbetsmoment för att säkra att slutprodukten möter de krav de ställt upp.

Förslag till nyttor under projektprocesserna:

-   Vilka olika skeden er man att man har under Ledamotshuset

    -   Vilka större beslut skall fattas i respektive skede?

    -   Vad behöver man för underlag?

-   Tydlig och effektiv kravställning - beskriv att det skapar en tydlighet i
    projekteringsgruppen (”kravdokument” + RFP)

-   Enkel och engagerande granskning – visa exempel på hur det kan gå till,
    fråga hur man tänker sig granskningsprocesserna under de olika skedena

-   Tydliga underlag för beslut och dialog med olika intressenter – exempel och
    fråga vilka intressenterna är och vilka processer och när ungefär i
    processen dessa dialoger behöver ske

-   Säkra och dokumentera miljöklassificering tidigt och kontinuerligt - vilka
    enheter är berörda?

Förslag till nyttor under förvaltningsprocesserna, inklusive leverans av
relationshandlingar:

-   Smidig uppföljning av verklig användning mot kravställning – Förklara och
    fråga vart dessa kravställningar i så fall ska in i befintliga system.

-   En informationskälla för areor, på alla ställen där de nyttjas – Vilka
    enheter behöver vilka areor till vad? System de ska in i?

-   Arkivering, *BIM-designmodell i orginalformat (Användningsområden, har tas
    den hand om på RDF, Underhåll, Ansvar och omfattning)*

-   Spårbarhet (Kvarter/Plan/Rum/System/Säkerhetsnivå) för byggdelar, inredning
    och komponenter i informationsleveransen för olika typer av användning,
    exempel se punkten nedan.

    -   Driftsinformation kopplad till aktuell byggdel, inredning och/eller
        digital komponent

    -   Till vad kan denna typ av information tänkas vara användbar till i er
        verksamhet?

-   Uppföljning av miljöklassificering

    -   Hur sker det?

I denna workshop vill vi arbeta både utifrån utpekade BIM-nyttor och projekt-
och förvaltningsprocesser för att kunna kravställa informationsbehovet.

Rubrik 1
========
Yadad yaday ydyayd
1. öldkflskdf
1. sdfölsdlöfk
1. söldjfsk
1. sdfsdfsdf

Please note that **only the first step** is covered by this gem — the rest happens on GitHub.com.  In particular, `markup` itself does no sanitization of the resulting HTML, as it expects that to be covered by whatever pipeline is consuming the HTML.

##asdasd##
dfgdfg

##sadfsdfs

###sdfsdfsd

####sdfsdfsdf

Please see our [contributing guidelines](CONTRIBUTING.md) before reporting an issue.

Rubrik 2
--------

The following markups are supported.  The dependencies listed are required if
you wish to run the library. You can also run `script/bootstrap` to fetch them all.

* [.markdown, .mdown, .mkdn, .md](http://daringfireball.net/projects/markdown/) -- `gem install commonmarker` (https://github.com/gjtorikian/commonmarker)
* [.textile](https://www.promptworks.com/textile) -- `gem install RedCloth`
* [.rdoc](https://rdoc.github.io/rdoc/) -- `gem install rdoc -v 3.6.1`
* [.org](http://orgmode.org/) -- `gem install org-ruby`
* [.creole](http://wikicreole.org/) -- `gem install creole`
* [.mediawiki, .wiki](http://www.mediawiki.org/wiki/Help:Formatting) -- `gem install wikicloth`
* [.rst](http://docutils.sourceforge.net/rst.html) -- `python3 -m pip install sphinx`
* [.asciidoc, .adoc, .asc](http://asciidoc.org/) -- `gem install asciidoctor` (http://asciidoctor.org)
* [.pod](http://search.cpan.org/dist/perl/pod/perlpod.pod) -- `Pod::Simple::XHTML`
  comes with Perl >= 5.10. Lower versions should install Pod::Simple from CPAN.


Installation
-----------

```
gem install github-markup
```

Usage
-----

Basic form:

```ruby
require 'github/markup'

GitHub::Markup.render('README.markdown', '* One\n* Two')
```

More realistic form:

```ruby
require 'github/markup'

GitHub::Markup.render(file, File.read(file))
```

And a convenience form:

```ruby
require 'github/markup'

GitHub::Markup.render_s(GitHub::Markups::MARKUP_MARKDOWN, '* One\n* Two')
```


Contributing
------------

See [Contributing](CONTRIBUTING.md).
