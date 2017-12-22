# julierme-archetype
Atividade Prática - Construção de Aplicativos
# **Instruções de Uso do Archetype:**  

## 1. Faça clone deste repositório:  
  
	  git clone https://github.com/ads-ifpb-praticas/julierme-archetype.git  
    
## 2. Entre dentro da pasta do projeto e execute:  
  
	  mvn clean install  
      
## 3. Vá para o diretório que deseja criar seu projeto e execute:  
  
	 mvn archetype:generate -DarchetypeGroupId=br.edu.ifpb.praticas
    -DarchetypeArtifactId=julierme-archetype
    -DarchetypeVersion=1.0-SNAPSHOT
    -DgroupId=br.com.your.domain
    -DartifactId=your-project-name
    -Dversion=1.0-SNAPSHOT
    -Dpackage=br.com.your.domain
