# SARTRE.md

# Suspicious Activity Reporting Tool for Recording Evidence (SARTRE).
___
**Aim:** Software solution for financial services, regulators and law enforcement to improve AML & CFT processes and enforcement.
**Challenge:** Efficient SAR evidence collection and packaging in a standardized format that can contribute to risk reduction. 
**Point of Failure:** Manual processes that are not shared across the industry. Inability to reliably prove data provenance without audit.
1. API login tied to users active directory credentials - e.g. tying it to a google identity in chrome
    - SU should be able to assign rights and privileges to general users (should be already aligned within internal processes)

2. Browser based plug-in interface
3. The ability to initiative a blockchain tied to a transaction based on set guidelines
    - Over $2000 amount
    - For transactions over $10000 a form 8300 is required - https://bsaefiling.fincen.treas.gov/docs/XMLUserGuide_FinCEN8300.pdf
    - Flagged by a member of staff 
    - Transactions on an account meet a designated value across a brief time period indicating obfuscation of intent
FINCEN guidelines on filing SAR- https://bsaefiling.fincen.treas.gov/docs/XMLUserGuide_FinCENSAR.pdf - Up to date to Feb 2020
                            CTR- https://bsaefiling.fincen.treas.gov/docs/XMLUserGuide_FinCENCTR.pdf - Up to date to April 2020
                            
4. The ability record all activity in the form of a transaction on-chain following the trigger
5. The ability to present these transactions in the form of a document/pdf demonstrating the chain-of-evidence.
    - should be compliant with the requirements for BSA filing. https://bsaefiling.fincen.treas.gov/Why_use_BSA_004.html

# Key Metrics 
___
Efficiency, compliance, and auditability

# FUTURE CONSIDERATIONS
[Designation of Exempted Persons - DOEP](https://bsaefiling.fincen.treas.gov/docs/XMLUserGuide_FinCENDOEP.pdf)

[BSA Batch e-filing testing](https://bsaefiling.fincen.treas.gov/docs/TestingProcedures.pdf)

[May need to incorporate the NAICS](https://bsaefiling.fincen.treas.gov/docs/NAICS.pdf)
