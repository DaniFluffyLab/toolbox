# =REMOVER_ACENTOS(texto_a_remover_acentos)

**Descrição:** Substitui os principais acentos da string para caracteres não-acentuados.

{{#include ../../_sysfiles/templates/cafe.md}}

## Versão para uso como função nomeada

**Nome da função:**
```
REMOVER_ACENTOS
```
**Marcadores de posição de argumentos::**
```
texto_a_remover_acentos
```

**Definição da fórmula:**
```
=REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(REGEXREPLACE(texto_a_remover_acentos;"(À|Á|Â|Ã|Ä|Å)";"A");"(À|Á|Â|Ã|Ä|Å)";"A");"(à|á|â|ã|ä|å)";"a");"Ç";"C");"ç";"c");"Ð";"D");"ð";"d");"(È|É|Ê|Ë)";"E");"(è|é|ê|ë)";"e");"(Ì|Í|Î|Ï)";"I");"(ì|í|î|ï)";"i");"Ñ";"N");"ñ";"n");"(Ò|Ó|Ô|Õ|Ö)";"O");"(ò|ó|ô|õ|ö)";"o");"Š";"S");"š";"s");"(Ù|Ú|Û|Ü)";"U");"(ù|ú|û|ü)";"u");"(Ÿ|Ý)";"Y");"(ý|ÿ)";"y");"Ž";"Z")
```