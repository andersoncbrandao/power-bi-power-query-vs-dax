// ================================================
// Power Query - Classificação por Faixas
// Exemplo reutilizável para Power BI
//
// ALTERE:
// 1. #"SuaTabela" -> Nome da etapa anterior
// 2. [Valor]      -> Coluna que deseja classificar
// 3. Os limites das faixas, se necessário
// ================================================

let
    Fonte = #"SuaTabela",

    #"Adicionar Faixa" =
        Table.AddColumn(
            Fonte,
            "Faixa",
            each
                if [Valor] <= 100 then "Baixo"
                else if [Valor] <= 500 then "Médio"
                else "Alto",
            type text
        )

in
    #"Adicionar Faixa"
