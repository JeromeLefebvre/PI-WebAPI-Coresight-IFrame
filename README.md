# PI Web API + Coresight - IFrame example

A very short sample that combines PI Web API and Coresight in the same website using iframes.

## Contents

* A simple index.html file that is split into two different iframes. The first iframe will display information comming from a PI Web API the second one will display a PI Coresight display.

## Getting Started

You will need a development/test PI System with PI Coresight and PI Web API accessible. You will need to edit the following two files to point them to the correct location:

* AFTree.html on Line 54 add in your own PI Web API service
* CoresightIframe.html on Line 23 add in your own PI Coresight address


## Requirements

These example was only tested with the following libraries and will probably not work with any others.

* PI Web API 2015 R3
* Coresight 2015
* Internet Explorer 11.0.29
* JQuery 2.2.2

The sample was also only tested using basic authentification for both PI Web API and PI Coresight.

## Licensing

Copyright 2016 OSIsoft, LLC.

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
Please see the file named [LICENSE.md](LICENSE.md).

