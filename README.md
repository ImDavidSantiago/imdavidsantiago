# 👋 Hola, soy **David Santiago**

### Systems Engineer · .NET & AI · Security Enthusiast

Desarrollador full‑stack especializado en C#/.NET, con maestría en seguridad informática y pasión por la IA. Mi misión es construir soluciones resilientes, seguras y escalables que automaticen procesos críticos.

---

## 🧑‍💻 About me in C\#

```csharp
using System;

// Declaración con constructor primario (C# 14)
public record DavidSantiago(string Name, bool Researcher, bool Developer, string[] Languages);

// Clase estática con método de extensión
public static class DavidSantiagoExtensions
{
    public static void SayHi(this DavidSantiago ds) =>
        Console.WriteLine($"Soy {ds.Name}. Visita mi sitio imdavidsantiago.dev");
}

// Código de arranque con top‑level statements (C# 14)
var me = new DavidSantiago(
    "David Santiago",
    true,
    true,
    new[] { "en_US", "es_MX" }
);
me.SayHi();
```

---

## 📫 Contacto

[imdavidsantiago.dev](https://imdavidsantiago.dev) · [LinkedIn](https://www.linkedin.com/in/imdavidsantiago) · [@imdavidsantiago](https://twitter.com/imdavidsantiago)

---

> *“Code is poetry when security and performance dance in harmony.”* — DS
