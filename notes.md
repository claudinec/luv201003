Title: Humanities computing  
Author: Claudine Chionh  
Affiliation: University of Melbourne  
Date: 2 March 2010  
Event: LUV meeting
LaTeX XSLT: beamer  
Theme: CambridgeUS

#### Overview

The Founders and Survivors project

Humanities computing

Why FOSS?

Challenges

Drupal in action: Data migration

## Founders and Survivors

#### The *Claudine*

Woolwich 24/aug/1821 to Hobart 15/dec/1821 -- 113 days at sea

160 male convicts boarded, 159 survived/landed (not a bad record)

#### Journal

![Journal](images/claudine33.png)

_Journal kept by surgeon: medical and other events_

#### Conduct registers

![John Astill](images/Astill-cr.jpg)

_Carried on ship and continued during sentence: convict's background, offence, trial, sentence, fate as convict_

#### Archives of Tasmania convict index

![convict search](images/Astill-aot.png)

_From paper to digital databases_

_Images of records; goal: transcribe, expand info available, access online_

#### Founders and Survivors

![Founders and Survivors](images/logo.jpg)

_Collaboration between historians, demographers, epidemiologists... UTas, Unimelb, ANU..._

_Survivors of convict system --> founders of population_

#### Van Diemen’s Land

Transportation period, 1803-1853

~ 1 million rows of data

Quantifiable data: conduct registers, BDM...

Text: journals, newspaper reports

#### Genealogists

What happened to convicts after they were freed?

Links with genealogists for lives of convicts and their families.

#### The 'factory plan'

![factory](images/factory33.png)

_Quantitative and text data and images._

_Separate areas/access for staff, volunteer researchers and public._

_Web system built in Drupal._

## Humanities computing

#### Old questions, new tools?

Digitisation

Analyse large[r] amounts of material

Public access and collaboration

_Following: some examples of humanities computing projects (diversity of sources and presentation)_

#### The Valley of the Shadow

![letter](images/valley.png)

_US Civil War_

_Transcriptions, images_

#### The Valley of the Shadow

![map](images/battlemap.png)

#### Old Bailey Online

![Old Bailey](images/oldbailey.png)

_transcriptions, images, corrections, additions_

#### Perseus Digital Library

Virgil's *Aeneid*

![Aeneid](images/aeneid60.png)

_translations, literary cross-references_

#### 'Libraries': Literary and linguistic applications

Index Thomisticus (1946)

Perseus

#### 'Archives': Historical applications

Digitisation

Data analysis

Collaboration

#### Digitisation

Documents

Images

Linked/cross-referenced presentation of sources

_Examples from FAS and related sources_

#### Tasmanian Police Gazette, 1861-1933

![Police gazette](images/police.png)

#### Surgeon's journals

![Marquis of Hastings journal](images/journal.png)

#### Conduct registers

![Marquis of Hastings conduct record](images/conduct.png)

#### Data analysis

![death rates](images/deathrates.png)

_analysis from combined sources_

#### GIS

![Mapping our Anzacs](images/mapping.png)

_mapping: geographic links, local, **personal**_

_'tribute to people important to you'_

_demystifying history_

#### Collaboration

![Hobart Town Gazette](images/htg.png)

_collaborative editing, corrections_

## Why FOSS?

#### Why FOSS?

Community of developers

Access

Values

#### Community of developers

Mutual support

Don’t reinvent the wheel

Using and adapting tools

_developers on humanities computing projects may be isolated and inexperienced_

#### Access

Make archival sources and research results accessible to general public

Sharing data with other researchers

#### Values

Public interest

Free access, free expression

Dialogue

Public participation

## Challenges

#### The Two Cultures

*The Two Cultures and the Scientific Revolution*

CP Snow, Rede Lecture, 1959

Literature/humanities vs science/tech

#### Many cultures?

Translating between academics, IT professionals, diverse public audience

Different priorities, research questions

_history, social sciences, public health, IT, non-tech users..._

#### Geeks and non-geeks

Non-geeks may not understand the values behind FOSS

Technology as magic

_colleagues as well as public can provide usability challenges_

#### Where do developers belong?

Identity crisis

'Digital humanities professional'?

Background -- IT or academic?

Autonomy

Career progression

Where do humanities computing projects belong?

## Data migration

#### Screenshot: Index record

TODO

_Drupal and humanities computing in action_

#### Why Drupal?

Modular

Define our own content types and views

Define user roles

Workflow

#### Index data

Access --> Excel --> CSV

--> Drupal?

Database on the web

#### Content Construction Kit

TODO URL

Define your own data structures in Drupal

TODO screenshot

#### Rules

<http://drupal.org/project/rules>

More powerful than core Trigger and Action modules

Generate a title for each node

`{index number} | {convict name} ({ship name})`

#### Views

TODO URL

Define your own views of content

#### Table Wizard

<http://drupal.org/project/tw>

Expose a MySQL table or CSV file to Views

#### Table analysis

TODO local copy of Skitch screenshot

http://img.skitch.com/20100217-q5fi5t93y2nnr6p6jr3ks4isae.jpg

#### Migrate

<http://drupal.org/project/migrate>

Map structure of external table to a Drupal data structure

Migrate Extras <http://drupal.org/project/migrate_extras> to migrate to CCK fields

#### Content set

TODO local copy of Skitch screenshot

http://img.skitch.com/20100217-mr3kkyq8gqmg4wumnqw844a387.jpg

#### Migrate dashboard

TODO local copy of Skitch screenshot

http://img.skitch.com/20100217-t937n4rq5tqx1iqqxhdqne5gn.jpg

#### Drush

Web-based dashboard good for testing on small samples

Drush: the Drupal Shell <http://drupal.org/project/drush>

(out of memory issues)

Run `drush migrate-import {content set}` from cron

Approx. one week to migrate ~ 80,000 records

## Where to from here?

#### Next stage of project

(manually) linking official index with public submissions

* later life stories
* WWI links

#### Links

The Valley of the Shadow <http://valley.lib.virginia.edu/>

Old Bailey Online <http://www.oldbaileyonline.org/>

Perseus Digital Library <http://www.perseus.tufts.edu/>

Index Thomisticus <http://www.corpusthomisticum.org/it/>

#### Links

Founders and Survivors <http://www.foundersandsurvivors.org/>

Mapping Our Anzacs <http://mappingouranzacs.naa.gov.au/>

Australian Newspapers (National Library) <http://newspapers.nla.gov.au/>

Essays in Humanities Computing <http://www.digitalhumanities.org/Essays/>

#### Questions/advice?

<http://www.foundersandsurvivors.org/>

<http://www.slideshare.net/claudinec>
