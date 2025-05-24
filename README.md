```js
import Desenvolvedor from "Gmmbr10";

class SobreMim extends Desenvolvedor {
  nome        = "Giovanne Monteiro de Melo";
  area        = ["Desenvolvedor Full Stack","Desenvolvedor Back End"];
  local       = "Arujá - São Paulo";
  aprendendo  = "Laravel";
  formacoes   = {
    "Técnico em Informática para a Internet": {
      instituicao:  "ETEC de Santa Isabel",
      inicio:       "Fev/2022",
      conclusao:    "Dez/2024",
      concluido:    true
    },
    "Tecnologia em Análise e Desenvolvimento de Sistemas": {
      instituicao:  "Centro Universitário ENIAC",
      inicio:       "Jan/2025",
      conclusao:    "Jun/2027",
      concluido:    false
    }
  };
}

class Skills extends Desenvolvedor {
  linguagens      = ["PHP","JavaScript","HTML","CSS"];
  banco_de_dados  = ["MySQL"];
  frameworks      = ["TailWind CSS","Bootstrap"];
  ferramentas     = ["VsCode","Git","Docker"];
}
```
