### about me
```golang
package main

import "fmt"

func main() {
	username := "vlaship"
	position := "Senior/Lead/Staff Software Engineer"
	linkedIn := "https://www.linkedin.com/in/shipovalov/"

	summary := `
	Senior Software Engineer with 10+ years of experience building backend systems in finance and e-commerce domains.
Developed services using microservices architecture, improved CI/CD processes, and migrated legacy code to modern codebases.
Strong expertise in Java, Kotlin, and Spring Framework. Have practical experience with distributed systems, messaging,
real-time data processing, Kubernetes, and Go. Enjoy mentoring junior engineers, testing new technologies through proof-of-concepts,
and delivering quality software from planning to production.
`

	skills := map[string][]string{
		"languages": {
			"Java", "Kotlin", "Golang", "JavaScript", "Rust", "C", "C++", "C#", "SQL", "Bash",
		},
		"queues": {
			"Apache ActiveMQ", "RabbitMQ", "Apache Kafka", "IBM MQ",
		},
		"databases": {
			"PostgreSQL", "MySQL", "SQLServer", "MongoDB", "Redis", "IBM BD2",
		},
		"db_migrations": {
			"Flyway", "Liquibase", "Goose",
		},
		"frameworks": {
			"Spring Framework", "Spring Boot", "Spring Cloud", "Spring Data", "Spring Security",
			"Spring Web", "Apache Camel", "JPA", "Hibernate", "QueryDSL", "MyBatis",
		},
		"cloud": {
			"AWS", "Azure",
		},
		"data": {
			"Azure Databricks", "Apache Spark", "Apache Storm",
		},
		"devops": {
			"Jenkins", "Gitlab", "GitHub Actions", "Docker", "Kubernetes", "Apache Maven", "Gradle",
			"BitBucket Pipelines", "SonarQube", "Nexus",
		},
		"testing": {
			"JUnit", "Mockito", "TestNG", "Jacoco", "Testify",
		},
		"bpmn": {
			"Camunda",
		},
		"protocols": {
			"HTTP", "REST", "GraphQL", "SOAP", "gRPC", "WebSockets", "AMQP", "JMS", "RSocket",
		},
		"UI": {
			"React", "JSP", "Thymeleaf",
		},
	}

	fmt.Println("Username: ", username)
	fmt.Println("Position: ", position)
	fmt.Println("LinkedIn: ", linkedIn)
	fmt.Println("Summary: ", summary)
	fmt.Println("Skills:")
	for key, value := range skills {
		fmt.Printf("%s:\n", key)
		for _, v := range value {
			fmt.Printf("\t%s\n", v)
		}
	}
}
```

### metrics
![Metrics](https://metrics.lecoq.io/vlaship?template=classic&languages=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&languages=false&languages.ignored=ruby%2C%20html%2C%20css%2C%20tsql&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.analysis.timeout.repositories=7.5&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&config.timezone=America%2FNew_York)

### me
[![GitHub](https://img.shields.io/badge/-vlaship-100000.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/vlaship)
[![LinkedIn](https://img.shields.io/badge/-shipovalov-0077B5.svg?style=for-the-badge&logo=Linkedin&logoColor=white)](https://linkedin.com/in/shipovalov)
[![Mastodon](https://img.shields.io/badge/-@vlaship-6364FF.svg?style=for-the-badge&logo=Mastodon&logoColor=white)](https://mas.to/@vlaship)
[![DEV.TO](https://img.shields.io/badge/-vlaship-0A0A0A.svg?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/vlaship)
[![LeetCode user vlaship](https://img.shields.io/badge/dynamic/json?style=for-the-badge&labelColor=black&color=%23ffa116&label=Solved&query=solvedOverTotal&url=https%3A%2F%2Fleetcode-badge.vercel.app%2Fapi%2Fusers%2Fvlaship&logo=leetcode&logoColor=yellow)](https://leetcode.com/vlaship/)
