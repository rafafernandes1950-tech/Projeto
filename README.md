# Projeto
neo4j
CREATE (n17:`NÓS`)-[:_RELATED {``: "PERTENCE"}]->(n24:`AÇÃO`)<-[:_RELATED {``: "PERTENCE"}]-(n12:`NÃO! NÃO OLHE!`)<-[:_RELATED {``: "DIRICTED"}]-(n22:`Jordan Peele`)-[:_RELATED {``: "DIRICTED"}]->(n17)<-[:_RELATED {``: "WATCHED"}]-(:Jessica)-[:_RELATED {``: "WATCHED"}]->(n12)<-[:_RELATED {``: "WATCHED"}]-(:Bia)-[:_RELATED {``: "WATCHED"}]->(n15:`A LENDA DE CANDYMAN`)<-[:_RELATED {``: "WATCHED"}]-(n3:Camila),
(n9:Esther)-[:_RELATED {``: "WATCHED"}]->(n20:` INFILTRADO NA KLAN`)<-[:_RELATED {``: "DIRICTED"}]-(n22)-[:_RELATED {``: "DIRICTED"}]->(n15)-[:_RELATED {``: "PERTENCE"}]->(n24)<-[:_RELATED {``: "PERTENCE"}]-(n21:AVATAR)<-[:_RELATED {``: "ACTED_IN"}]-(n27:`Sam Worthington`)-[:_RELATED {``: "ACTED_IN"}]->(n18:`Avatar: O Caminho da Água`)<-[:_RELATED {``: "ACTED_IN"}]-(n26:`Kate Winslet`),
(n27)-[:_RELATED {``: "ACTED_IN"}]->(n16:`Avatar: Fogo e Cinzas`)-[:_RELATED {``: "PERTENCE"}]->(n24)<-[:_RELATED {``: "PERTENCE"}]-(n18)<-[:_RELATED {``: "DIRICTED"}]-(n23:`James Cameron`)-[:_RELATED {``: "DIRICTED"}]->(n16)<-[:_RELATED {``: "WATCHED"}]-(n8:Gabriela)-[:_RELATED {``: "WATCHED"}]->(n21)<-[:_RELATED {``: "WATCHED"}]-(n7:`Inês`)-[:_RELATED {``: "WATCHED"}]->(n16)<-[:_RELATED {``: "WATCHED"}]-(n10:Helen)-[:_RELATED {``: "WATCHED"}]->(n18),
(n29:`Elisabeth Moss`)-[:_RELATED {``: "ACTED_IN"}]->(n13:`Alita: Anjo de Combate`)-[:_RELATED {``: "PERTENCE"}]->(n25:AVENTURA)<-[:_RELATED {``: "PERTENCE"}]-(n20)<-[:_RELATED {``: "ACTED_IN"}]-(n29),
(n14:`Titanic `)<-[:_RELATED {``: "DIRICTED"}]-(n23)-[:_RELATED {``: "DIRICTED"}]->(n21)<-[:_RELATED {``: "ACTED_IN"}]-(n26)-[:_RELATED {``: "ACTED_IN"}]->(n14)-[:_RELATED {``: "PERTENCE"}]->(n25)<-[:_RELATED {``: "PERTENCE"}]-(n19:`TOY STORY 4`)<-[:_RELATED {``: "ACTED_IN"}]-(n28:`Adam Driver`)-[:_RELATED {``: "ACTED_IN"}]->(n20)<-[:_RELATED {``: "WATCHED"}]-(n3),
(n26)-[:_RELATED {``: "ACTED_IN"}]->(n16),
(n28)-[:_RELATED {``: "ACTED_IN"}]->(n13)<-[:_RELATED {``: "DIRICTED"}]-(n23),
(n22)-[:_RELATED {``: "DIRICTED"}]->(n19)<-[:_RELATED {``: "WATCHED"}]-(n5:Duda),
(n8)-[:_RELATED {``: "WATCHED"}]->(n18)<-[:_RELATED {``: "WATCHED"}]-(n7),
(n10)-[:_RELATED {``: "WATCHED"}]->(n21),
(n5)-[:_RELATED {``: "WATCHED"}]->(n13)<-[:_RELATED {``: "WATCHED"}]-(:Ana)-[:_RELATED {``: "WATCHED"}]->(n19)<-[:_RELATED {``: "WATCHED"}]-(n9),
(n3)-[:_RELATED {``: "WATCHED"}]->(n19)<-[:_RELATED {``: "WATCHED"}]-(n4:Fabia),
(n4)-[:_RELATED {``: "WATCHED"}]->(n20),
()
