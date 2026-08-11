# TechAyo Ecosystem

TechAyo LTD builds and operates digital systems for businesses: from websites and internal operations to applied AI, automation, custom software, and owned product infrastructure.

A useful way to understand the company is as a technology studio with an increasingly integrated stack rather than as a conventional web agency. TechAyo combines delivery work with owned technology that can be reused across products and customer systems.

## The ecosystem

The current technology direction can be understood in layers:

```text
TechAyo LTD
    |
    +-- FNLLA        application and web infrastructure
    +-- Fionn        persistent intelligence and AI R&D
    +-- TechAyo      company, client and operations platform
    +-- Products     owned vertical software such as Paydeck
    +-- Client systems built and maintained on the same foundations
```

These projects remain separate products with separate ownership, release, licensing and support boundaries. The diagram describes the strategic relationship between them, not a promise that every TechAyo product currently depends on every other layer.

## FNLLA: application infrastructure

FNLLA is TechAyo's compact open-source PHP framework for server-rendered websites and application surfaces. It provides a maintained application foundation for routing, controllers, views, authentication, authorisation, database work, operational tooling and the integrated FNLLA UI runtime.

Within the wider TechAyo ecosystem, FNLLA is the application layer: a reusable foundation for building maintainable business systems without treating every delivery as an unrelated stack.

## Fionn: intelligence infrastructure

Fionn is TechAyo's persistent-personal-intelligence research and product project. Its long-term loop is:

```text
Memory -> Understanding -> Reasoning -> Decisions -> Outcomes -> Learning
```

Fionn is deliberately defined as more than a single model checkpoint. Its architecture separates durable system concerns such as identity, memory, experience, capabilities, behaviour and orchestration from replaceable model packages.

The current model foundation is intentionally small and locally understandable: tokenisation, a decoder-only Transformer in PyTorch, training, evaluation, checkpointing, packaging and local inference. Fionn is not positioned as a wrapper around a third-party model API, nor is the current model presented as a frontier general-purpose LLM.

The strategic value of this architecture is continuity: model packages can improve or be replaced while the wider intelligence system can preserve governed memory, experience and product behaviour.

## Products and delivery

TechAyo uses its engineering capability in several directions:

- owned digital products and vertical software;
- customer websites and operational systems;
- applied AI and workflow automation;
- internal client and delivery operations;
- reusable framework, runtime and release infrastructure.

Paydeck is an example of the owned-product direction: a payroll platform designed around multi-tenant operations, automation and AI-supported workflows. Customer systems such as the Perthshire Cleaning platform demonstrate the delivery direction, where a public website can coexist with CRM, administration, employee and operational surfaces.

## The operating idea

The long-term opportunity is not simply to own more repositories. It is to make useful technology compound across the company.

A capability solved at the framework or infrastructure layer can be reused by multiple products. Product and customer delivery can expose real operational requirements. Those requirements can inform reusable infrastructure where appropriate, while product-specific code and customer ownership boundaries remain explicit.

This creates a potential reinforcing loop:

```text
Infrastructure -> Products -> Real-world use -> Operational learning
       ^                                      |
       +--------------------------------------+
```

## Positioning

A concise description of TechAyo is:

> TechAyo builds and operates digital systems for businesses, from websites and internal operations to AI automation and custom software, supported by technology it develops and maintains itself.

An even shorter expression of the product philosophy is:

> TechAyo turns business operations into software.

These statements describe the direction of the ecosystem without implying that every capability is mature, hosted at scale, or commercially available today. Individual repository documentation remains the source of truth for current product status and readiness.
