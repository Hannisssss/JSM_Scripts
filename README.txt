Datum: 2025-06-15
Av: [Hanna Sjöström]
Kandidatprojekt, Mittuniversitetet
Civilingenjör Datateknik

---

INNEHÅLL:
- csn-jsm-export-20250610.xml  
    → XML-export av hela Jira Service Management-projektet.  
    → Importeras via Adminpanelen i Jira
- css
    → CSS som anpassar portalen, appliceras som web resource genom ScriptRunner
- Groovy
    → Skript som skapar anpassade fält, appliceras genom ScriptRunner
---

   ÅTERSTÄLLNING OCH INSTALLATION:
1. Installera Jira Service Management Data Center (v10.5.1).
2. Kopiera XML-filen till:  
   `C:\jira-home\import\csn-jsm-export-20250610.xml`
3. Gå till:  
   System > Import & Export > Restore System
4. Välj XML-filen ovan och starta återställning.

---
