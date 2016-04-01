# probedock-uid-maven-plugin

> A plugin to generate a unique report id for Probe Dock.

## Usage

1. Put the following dependency in your pom.xml

```xml
<plugin>
	<groupId>io.probedock.maven.plugins</groupId>
	<artifactId>probedock-uid-maven-plugin</artifactId>
	<version>0.0.1</version>
	<executions>
		<execution>
			<goals>
				<goal>generate</goal>
			</goals>
		</execution>
	</executions>

	<!--
		Optional configuration if you want to have a property of a different name.
		The default proerty name is: probedock.report.uid
	-->
	<configuration>
		<propertyName>custom.property.name</propertyName>
	</configuration>
</plugin>
```

### Requirements

* Java 6+

## Contributing

* [Fork](https://help.github.com/articles/fork-a-repo)
* Create a topic branch - `git checkout -b feature`
* Push to your branch - `git push origin feature`
* Create a [pull request](http://help.github.com/pull-requests/) from your branch

Please add a changelog entry with your name for new features and bug fixes.

## License

**probedock-uid-maven-plugin** is licensed under the [MIT License](http://opensource.org/licenses/MIT).
See [LICENSE.txt](LICENSE.txt) for the full text.
