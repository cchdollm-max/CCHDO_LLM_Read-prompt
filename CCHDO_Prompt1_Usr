Document: {{ $json.filename }}
Pages reported by parser: {{ $json.page_count }}
 
Parsed cruise report content:
{{ $json.pages.map(p => "--- PAGE " + p.page_number + " ---\nTEXT:\n" + (p.text || "") + "\n\nTABLES:\n" + JSON.stringify(p.tables || [])).join("\n\n") }}
 
Extract PIs, floats, and instruments from the content above, following the system rules.
Return strict JSON only.
 
