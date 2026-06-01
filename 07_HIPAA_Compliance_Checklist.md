|  |
| --- |
| **07 · HIPAA & Compliance Checklist**  Healthcare Software PM Template Library |

|  |
| --- |
| **DOCUMENT INFO** |

**Feature / Release:** *\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_*

**Reviewed By:** *\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_*

**Date:** *\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_*

**Legal / Compliance Approver:** *\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_*

|  |
| --- |
| **1. PHI IDENTIFICATION** |

* Identified all PHI data elements involved (name, DOB, MRN, diagnosis, etc.)
* Confirmed PHI is necessary and minimum for the feature to function
* Documented PHI data flow (collection → storage → transmission → deletion)

|  |
| --- |
| **2. TECHNICAL SAFEGUARDS** |

* PHI encrypted at rest (AES-256 or equivalent)
* PHI encrypted in transit (TLS 1.2+ / HTTPS)
* Access controls: Role-Based Access Control (RBAC) implemented
* Automatic session timeout enforced for PHI-accessible screens
* Audit logging enabled: captures user, timestamp, action, and PHI accessed
* Unique user IDs — no shared credentials for PHI access
* Emergency access procedure documented

|  |
| --- |
| **3. ADMINISTRATIVE SAFEGUARDS** |

* Business Associate Agreement (BAA) in place with all third-party vendors handling PHI
* Workforce training on HIPAA completed and documented
* Data breach response plan referenced / updated
* Risk analysis completed for new PHI exposure surface

|  |
| --- |
| **4. PHYSICAL SAFEGUARDS** |

* PHI not stored on local devices without encryption
* Physical media containing PHI properly disposed (NIST 800-88)

|  |
| --- |
| **5. INTEROPERABILITY COMPLIANCE** |

* HL7 FHIR R4 compliance verified for data exchange (if applicable)
* HL7 v2 message formats validated (if applicable)
* SMART on FHIR authorization used for EHR integration (if applicable)
* ONC information blocking rule reviewed for patient data access

|  |
| --- |
| **6. SIGN-OFF** |

|  |  |  |
| --- | --- | --- |
| **Role** | **Name** | **Signature / Date** |
| PM |  |  |
| Tech Lead |  |  |
| Compliance / Legal |  |  |
