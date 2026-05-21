# min-root-spring

## Purpose
Spring Boot parent POM for Spring-based min-* projects, extending Spring Boot Starter Parent.

## Guidelines
- **Architecture**: Foundation POM for Spring projects
- **Dependencies**: None (parent only)
- **Parent**: spring-boot-starter-parent (3.5.0)
- **Java Version**: 21
- **Usage**: Parent for Spring-based applications

## Key Features
- Inherits all Spring Boot capabilities
- Same plugin management as min-root
- Distribution management for private repository
- Java 21 compilation target

## Usage in Projects
```xml
<parent>
    <groupId>com.olexyn</groupId>
    <artifactId>min-root-spring</artifactId>
    <version>21.0.0</version>
</parent>
```

## Relationship to min-root
- **Complementary**: Use min-root for plain Java, min-root-spring for Spring
- **Consistent**: Same version numbering and distribution management
- **Aligned**: Both target Java 21 and use same plugin versions

## Maintenance
- Keep Spring Boot version current with security updates
- Maintain version alignment with min-root
- Coordinate plugin version updates
- Ensure distribution management stays consistent

## When to Use
- **Use min-root-spring**: For Spring Boot applications
- **Use min-root**: For plain Java libraries and utilities
- **Never mix**: Don't use both in the same project hierarchy