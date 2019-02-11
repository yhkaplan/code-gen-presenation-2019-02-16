# [fit] Code Generation

---

# [fit] What you can do

---

# Generate
    - Mocks
    - Tests
    - Lenses

---

# Test specific
- [Cuckoo](https://github.com/Brightify/Cuckoo)
- [SwiftyMock](https://github.com/MakeAWishFoundation/SwiftyMocky)

---

# Network test specific
- [Mockingjay](https://github.com/kylef/Mockingjay)
- [Kakapo](https://github.com/devlucky/Kakapo)

---

# Type safe resources
    - Storyboards
    - Assets
    - Plists
    - json (useful in tests)
    - Localizable.strings

---

# [fit] Tools of the trade

---

# General code generation
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery)
- [Gyb](https://github.com/jph00/gyb)
- [Gyb (Swift Repo)](https://github.com/apple/swift/blob/664e5659c50fb35c6b8e08d05ca6a4e81bdae7f3/utils/gyb.py)

---

# Safe assets
- [R.swift](https://github.com/mac-cain13/R.swift)
- [SwiftGen](https://github.com/SwiftGen/SwiftGen)

---

# Share model data w/ server
- Swagger
- GraphQL + Apollo

---

# Demo of SwiftGen
- Why I prefer SwiftGen over R.Swift

---

# [fit] The Stencil templating language

---

# It's just Swift (with special markers)

- Variables: `{{}}`
- Tags (control flow): `{%%}`
- Comments: `{##}`

---

# Variables

```swift
There are {{ people.count }} people. {{ people.first }} is the first
person, followed by {{ people.1 }}.
```

---

# If statements

```swift
{% if variable %}
  {{ variable }} was found.
{% endif %}
```

---

# Loops

```swift
{% for item in items %}
  {{ item }}
{% endfor %}
```

---

# [fit] Demo of Sourcery

---

# [fit] Mocks

---

# [fit] Tests

---

# [fit] Lenses

---

# Nice Templates
- https://github.com/AliSoftware/SourceryTemplates
- https://github.com/Liquidsoul/Sourcery-AutoJSONSerializable
