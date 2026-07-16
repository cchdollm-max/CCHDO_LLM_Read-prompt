Cruise: {{ $json.cruise }}
 
Parameter definitions (parameters.json):
{{ JSON.stringify($json.parameter_definitions || {}) }}
 
Parameter list without flags:
{{ JSON.stringify($json.parameter_list_without_flags || []) }}
 
Parameter list with flags:
{{ JSON.stringify($json.parameter_list_with_flags || []) }}
 
Data-file / Exchange header:
{{ JSON.stringify($json.data_file_header || []) }}
 
Stage 1 PI output:
{{ JSON.stringify($json.pis || []) }}
 
Cruise-report context:
{{ JSON.stringify($json.context || {}) }}
 
Match each parameter to the Stage 1 PI records that are responsible for it, following
the system rules. Return strict JSON only.
 
