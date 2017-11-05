---
layout: student
esr: 7
name: Dennis Diefenbach
image: Dennis_Diefenbach.jpg
project: Question Answering over Knowledge-Bases
host: st-etienne
start-date: 2015-06-01
supervisors:
  - Pierre Maret
  - Kamal Singh
  - Andreas Both
publications:
  - Singh2016a
  - Both2016
  - Diefenbach2016a
  - Singh2016b
  - Diefenbach2016b
  - Diefenbach2016c
  - Diefenbach2017a
  - Diefenabch2017b
  - Diefenbach2017c
  - Diefenbach2017d
  - Diefenbach2017e
  - Diefenbach2017f
  - Diefenbach2017g
email: dennis.diefenbach@univ-st-etienne.fr
github: D063520
scholar: IHizMRoAAAAJ&hl
students:
  - st1:
    start: 09/16
    end: 12/16
    name: Shanzay Amjad
    topic: Designing a front-end for QA systems
  - st2:
    start: 05/17
    end: 07/17
    name: Youssef Dridi
    topic: Generating a user understandable representation of a SPARQL query
  - st3:
    start: 05/17
    end: 07/17
    name: Shanzay Amjad
    topic: Transform an industrial dataset in RDF to make QA on it 
---
Question Answering (QA) over Knowledge-Bases (KBs) is a very interesting research topic. A KB is a collection of facts. For example, DBpedia is a KB containing facts collected from <a href="http://www.wikipedia.org/">Wikipedia</a> like the birth date of persons, capitals of countries, museums in cities and many more. These facts are stored in machine readable formats and they can be retrieved using queries over databases. The information contained in such KBs can be very interesting for end-users, but we cannot require from them to write a formal query over a database (e.g. in <a href="https://www.w3.org/TR/rdf-sparql-query/">SPARQL</a>). This is where Question Answering over KBs comes into play, i.e. to automatically transform a natural language question like "Who is the mayor of Paris?" to a formal query that can be executed over a KB.

My research follows two directions. First, to create a framework, called <a href="https://github.com/WDAqua/Qanary#readme">Qanary</a>, that allows to reuse and combine technologies that are already used in QA systems. This is done in collaboration with <a href="/supervisors/andreas-both/">Andreas Both</a> (Supervisor, Datev eG) and <a href="/students/kuldeep-singh/">Kuldeep Singh</a> (ESR 8, FRAUENHOFER). Second, considering the lessons learned from previous QA approaches, we are building a novel question answering system using new technologies. Currently it is enabled to query <a href="http://wiki.dbpedia.org/">DBpedia</a>, <a href="https://www.wikidata.org/">Wikidata</a>, <a href="">MusicBrainz (the an open music encyclopedia)</a> and <a href="http://dblp.org/">DBLP (computer science bibliography)</a> using natural language questions and keywords. Moreover, it is possible to query Wikidata using English, French, German, Spanish and Italian. Visit it under <a href="http://www.wdaqua.eu/qa">www.wdaqua.eu/qa</a>.
