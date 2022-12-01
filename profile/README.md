# Welcome to the Figurate project

Maintaining Cloud infrastructure is complex, with tools and methodologies still in their infancy. Figurate focuses on patterns and blueprints
that deliver key software design principles, such as modularity, reusability and separation of concerns, to Infrastructure-as-code (IaC).

## Modules

Software development has long benefitted from the ability to reuse proven code in the form of libraries. With IaC we see similar benefits in
Terraform modules, Ansible roles, and other widely published shared code repositories.

Shared modules must be throroughly tested, versioned and regularly updated to provide a stable foundation for building blueprints.

## Blueprints

Blueprints are a combination of published modules and sensible defaults, that enable us to deploy tested architectures with a minimum of
effort. The importance of defaults is to allow an evolution of infrastructure from simple to complex as a deployed solution matures over
time.
