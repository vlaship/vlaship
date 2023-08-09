### about me
```golang
package main

import "fmt"

func main() {
	username := "vlaship"
	position := "Senior Software Engineer"
	linkedIn := "https://www.linkedin.com/in/shipovalov/"

	summary := `
    I am a hard worker who enjoys tackling complex problems. I spent the past years in an Agile development process using Scrum and Kanban, pushing our releases through CI/CD using Jenkins, Gitlab, and Github Actions as part of a DevOps process. I am very autonomous, capable of solving complex problems, and consistently delivering on-time results. I am highly skilled in Java, Kotlin, Spring Framework, Hibernate, SQL and NoSQL databases, BigData technologies, DevOps tools, etc. I have had experience managing a small team of developers during a 3-month delivery effort and would like to do more of that. I have also helped evaluate new developers and SRE candidates during the interview process.
    I am looking for an opportunity to work with a small team of dynamic developers where I can learn and grow. I am particularly interested in improving my management and leadership skills. I am open to new languages, technologies, and practices.
    `

	skills := make(map[string][]string)
	skills["languages"] = []string{
		"Java", "Kotlin", "Golang", "JavaScript", "Rust", "C", "C++", "C#", "SQL", "Bash",
	}
	skills["queues"] = []string{
		"Apache ActiveMQ", "RabbitMQ", "Apache Kafka", "IBM MQ",
	}
	skills["databases"] = []string{
		"PostgreSQL", "MySQL", "SQLServer", "MongoDB", "Redis", "IBM BD2",
	}
	skills["db_migration"] = []string{
		"Flyway", "Liquibase", "Goose",
	}
	skills["frameworks"] = []string{
		"Spring Framework", "Spring Boot", "Spring Cloud", "Spring Data", "Spring Security", "Spring Web", "Apache Camel", "JPA", "Hibernate", "QueryDSL", "MyBatis",
	}
	skills["cloud"] = []string{
		"AWS", "Azure",
	}
	skills["data"] = []string{
		"Azure Databricks", "Apache Spark", "Apache Storm",
	}
	skills["devops"] = []string{
		"Jenkins", "Gitlab", "Github Actions", "Docker", "Kubernetes", "Apache Maven", "Gradle", "BitBucket Pipelines", "SonarQube", "Nexus",
	}
	skills["testing"] = []string{
		"JUnit", "Mockito", "TestNG", "Jacoco",
	}
	skills["bpmn"] = []string{
		"Camunda",
	}
	skills["protocols"] = []string{
		"HTTP", "REST", "GraphQL", "SOAP", "gRPC", "WebSockets", "AMQP", "JMS", "RSocket",
	}
	skills["UI"] = []string{
		"React", "JSP", "Thymeleaf",
	}

	fmt.Println("Username: ", username)
	fmt.Println("Position: ", position)
	fmt.Println("LinkedIn: ", linkedIn)
	fmt.Println("Summary: ", summary)
	fmt.Println("Skills:")
	for key, value := range skills {
		fmt.Printf("%s:\n", key)
		for _, v := range value {
			fmt.Println("    ", v)
		}
	}
}
```

### contact me
<a href="https://linkedin.com/in/shipovalov"><img src="https://img.shields.io/badge/-shipovalov-0077B5?style=flat&logo=Linkedin&logoColor=white"/></a>

### github metrics
![Metrics](https://metrics.lecoq.io/vlaship?template=classic&languages=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&languages=false&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.analysis.timeout.repositories=7.5&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&config.timezone=America%2FNew_York)

