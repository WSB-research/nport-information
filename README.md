# nport-information
Information and DD on the NPORT-P XML specification for reporting fund holdings data -valkn0t

## Overview

- From the SEC: "*Form N-PORT is the reporting form that is to be used for monthly reports of Funds other than money market funds and SBICs under section 30(b) of the Act, as required by rule 30b1-9 under the Act (17 CFR 270.30b1-9). Funds must report information about their portfolios and each of their portfolio holdings as of the last business day, or last calendar
day, of the month.*"
- Seems like `NPORT-P` is the XML file, `NPORT-EX` is the "Exhibit" file, looks exactly like an `NCSR`. `NPORT-NP` is "Not Public". 

## NPORT Types: `NPORT-P NPORT-P/A NPORT-EX NPORT-EX/A`

- NPORT-P: Monthly Portfolio Investments Report on Form N-PORT (Public).
- NPORT-P/A: Amendment to Monthly Portfolio Investments Report on Form N-PORT (Public).
- NPORT-NP: Monthly Portfolio Investments Report on Form N-PORT (Non-Public).
- NPORT-NP/A: Amendment to Monthly Portfolio Investments Report on Form N-PORT (Non-Public).
- NPORT-EX: Portfolio Holdings Exhibit to Form N-PORT.
- NPORT-EX/A: Amendment to Portfolio Holdings Exhibit to Form N-PORT.
- The new NPORT-P and NPORT-NP submission form types will be accepted from the EDGAR Filing Website via filer-constructed XML submissions, as described in the "EDGAR Form N-PORT XML Technical Specification" document available on the SEC's Public Website (https://www.sec.gov/info/edgar/tech-specs). The new NPORT-EX submission form types can be accessed by selecting the ‘EDGARLink Online Form Submission’ link on the EDGAR Filing Website. Additionally, filers may construct XML submissions for these submission form types by following the "EDGARLink Online XML Technical Specification" document available on the SEC's Public Website (https://www.sec.gov/info/edgar/tech-specs).


## Links

- SEC report document search for NPORT forms with keyword "corporate": https://sec.report/Document/Header/?formType=NPORT-P&keyword=corporate#results
- Good write-up/explanation on SEC modernization rules and forms: https://www.pepperlaw.com/resource/29644/7E0 (also uploaded to repository in case link fails) 