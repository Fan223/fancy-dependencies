# Fancy-BOM

Centralized dependency version alignment.

```xml

<dependencies>
    <dependency>
        <groupId>fan</groupId>
        <artifactId>fancy-bom</artifactId>
        <version>${revision}</version>
        <type>pom</type>
        <scope>import</scope>
    </dependency>
</dependencies>
```

# Fancy-Parent

Unified build conventions and plugin configuration.

```xml

<parent>
    <groupId>fan</groupId>
    <artifactId>fancy-parent</artifactId>
    <version>${revision}</version>
</parent>
```
