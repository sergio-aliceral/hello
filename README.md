# Objetivo
API Hello World com Spring Boot.

## Iniciando

- `git clone https://github.com/sergio-aliceral/hello.git`
- `cd hello`

## Pré-requisitos
- `mvn --version`<br>

Você deverá ver a indicação da versão do Maven instalada e a versão do JDK. Observe que o JDK é obrigatório, assim como a definição das variáveis de ambiente **JAVA_HOME** e **M2_HOME**.

## Limpar, compilar e empacotar
- `mvn clean install`<br>

Gera arquivo _hello.jar_ no diretório _target_.

## Executando a aplicação
- `java -jar target/hello-1.0.jar`<br>

Executa o aplicativo por meio do arquivo jar criado pelo comando `mvn clean install`, conforme comentado anteriormente.

- Abra o endereço _http://localhost:8080/hello_ no seu navegador, ou forneça a seguinte URL para um nome específico _http://localhost:8080/hello?name=Sérgio_.
