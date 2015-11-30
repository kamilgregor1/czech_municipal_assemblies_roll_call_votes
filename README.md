# Roll call results of vote events during plenary sessions of municipal assemblies in Czech Republic

## How to cite

GREGOR, Kamil (2015). "Roll call results of vote events during plenary sessions of municipal assemblies in Czech Republic" [https://github.com/kamilgregor1/czech_municipal_assemblies_roll_call_votes].

## Data availability

Municipalities are included depending on <a href = "http://blog.openingparliament.org/post/108553329888/surveying-parliamentary-data-openness-in-6300"><strong>data availability</strong></a>. Data from the Municipal Assembly of Prague are scraped by <a href = "https://github.com/michalskop/datapackages"><strong>Michal Škop</strong></a> and updated irregularly.

Most municipalities included here have started to record and/or publish roll call results of plenary vote events only recently. If roll call results are available, it usually means that results of all or almost all vote events are recorded by names of individual voters. In almost all municipalities, votes of all voters are recorded (not just those that were present during voting).

## Data specification

Data on each municipality are split into folders by electoral terms. Each term contains CSV files on party groups, vote events, votes in a given term. If more information than just voters' names is available, it also contains a CSV file on voters. The following variables are included in the files:

### groups

<code>id</code>                       a unique identifier of a party group, usually its abbreviation
<code>legislative_session:id</code>

Types of information available in each municipality vary. See an overview of variables in the CSV files and examples of their values.

## Data updates

In case of several larger municipalities that publish roll call results in the HTML format, there are live scrapers of the official municipal websites that run every Monday. In other cases, the data is recorded manually based on minutes from the plenary sessions. This data is updated irregularly.

## Miscellaneous information

In almost all municipalities, there are the following voting options:

<ul>
<li><em>Pro / Ano</em> - In favour / Yea
<li><em>Proti / Ne</em> - Against / Nay
<li><em>Zdržel se</em> - Abstained
<li><em>Nehlasoval</em> - Not voted (e.i. was present but did not indicate any of the options above)
<li><em>Nepřítomen</em> - Absent
</ul>

The quorum is almost always calculated out of all voters in the assembly (not just those present). This means that abstention, not voting and even absenting is <em>de facto</em> identical to voting against.

In some municipalities, voters are organized in formal party groups (<em>zastupitelský klub</em>). In most cases, however, voters' affiliations to political parties are not formally reflected in the assembly. A variable <code>group:id</code> usually indicates a political party that proposed a given voter as a candidate in municipal elections (<em>navrhující strana</em>). This is not identical to a name of a candidate list.

## Author

Created by <a href = "https://twitter.com/kamilgregor"><strong>Kamil Gregor</strong></a> (with <a href = "http://kohovolit.eu/en/"><strong>KohoVolit.eu</strong></a> and <a href = "http://www.muni.cz/"><strong>Masaryk University</strong></a>) in the <em>Otevírání výsledků hlasování na obecních zastupitelstvech</em> (<em>Opening up voting results in municipal assemblies</em>) project supported by the <a href = "http://www.osf.cz"><strong>Open Society Fund Prague</strong></a>. The data is in the <a href = "http://popoloproject.com/"><strong>Popolo</strong></a> data standard. 

## License

<a href = "http://creativecommons.org/licenses/by/4.0"><strong>Creative Commons BY 4.0</strong></a>.
