================
 - [Overview](#overview)
 - [Methodology](#method)
 - [Limitations](#limit)
 - [License](#license)

## Overview
### Eviction numbers are climbing back toward pre-pandemic highs

After falling to an unprecedented low during the pandemic, eviction numbers are creeping back toward 2019 rates in Maryland, according to data from the Maryland Judiciary.

For decades, Maryland hospitals have sued patients with unpaid bills, amassing hundreds of millions of dollars in judgments since 2000. But this year, something curious happened.

The judgments virtually stopped, according to an analysis of court data by The Baltimore Banner. Why is not entirely clear. Bad publicity could be a factor — hospitals have scaled back legal action in the past when under scrutiny for suing some of their poorest patients. There's also a new state law requiring hospitals offer payment plans patients can afford before they sue. 

Now advocates and observers wonder what steps hospitals will take to collect on unpaid bills or if they will start suing again. Medical debt is expected to tick up this year as Marylanders lose Medicaid coverage they’d been allowed to keep during the coronavirus pandemic. 

Read The Baltimore Banner's story [Maryland hospitals stopped suing patients with unpaid bills. Why is a mystery.]().

This story was published in partnership with the podcast “An Arm and a Leg” and Scripps News.

This work was supported by the McGraw Center for Business Journalism at the Craig Newmark School of Journalism at the City University of New York.

<a id="method"></a>

## Methodology
### How we analyzed Maryland Judiciary court data

The Banner analyzed all circuit court cases that involved a judgment. CaseHarvester parsed scraped court cases in five different formats: Circuit Court (CC), District Court (DSCIVIL), Prince George's County Circuit Court (PGV) and Montgomery County (MCCI). Hospitals were identified by matching the plaintiff name with a database of Maryland Hospitals. The methodology to parse each was similar but differing formats required slightly different code.

Hospitals were identified by comparing plaintiff names of to a Maryland TK Department of hospitals database. The matches were judged using JW, LW and N-GRAM. If a match score was .10/10 or lower, or matched a predetermined string, we kept the match. 

Raw data that included these matches were matched in OpenRefine using each key collision method. Each cluster was manually reviewed. Three hospitals were especially troubling during this analysis: Pennisula, Southern and Fort Washington. These hospitals were manually matched.

The Banner only counted principal amounts as judgments. The totals would increase if court fees, attorney's fees and interest were included.

<a id="limit"></a>
## Limitations


These databases of plaintiffs should not be used for any other analysis. In targeting Maryland's hospitals, like names that were not hospitals were combined even though they are different entities. Care was only taken when clustering Maryland hospitals. This was done to remove them from clustering options, greatly speeding up the clustering process. 


<a id="license"></a>

## License

Copyright 2022, The Venetoulis Institute for Local Journalism

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
