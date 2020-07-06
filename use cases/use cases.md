# SolidLoV Requirements and Use Cases

## Summary

  - [Requirements](#Requirements)
  - [Use Cases](#Use-Cases)
  - [Terms](#Terms)

## Requirements

- Vocabularies are constantly evolving
- Creating and maintaining vocabularies is a social enterprise
- There is no central source of truth for vocabularies
- Vocabularies can be private



## Use Cases

- An agent maintains a vocabulary for subscribers by hosting it on a pod and makes it available for copying, term searches and sparql queries.  

- An agent searches for a vocabulary term based on key words and/or app context, for use in autocomplete on form filling and creation.  Local, remote, descendant and ancestral vocabularies are searched in an order specified by search configuration.

- An agent creates or reuses a search configuration that specifies ordering of local, remote, descendant, and ancestral vocabularies for search

- An agent creates a descendant vocabulary by copying an ancestral vocabulary and making changes to it.  Descendant and ancestral vocabularies can be either local or remote.

- An agent that uses a vocabulary subscribes to updates

- An agent maintains a vocabulary and and sends information about updates to subscribers

- An agent that maintains a vocabulary subscribes to updates to ancestral vocabularies

- An agent that maintains a vocabulary subscribes to updates to descendant vocabularies

- An agent restricts access to a vocabulary to certain persons or groups

- An agent compares one vocabulary to another by measures such as equivalence, similarity, scope, structure, usage, provenance or fitness for purpose.

- An agent collects local vocabularies and optimizes them for search efficiency

## Terms

- Vocabulary: An ontology in OWL or RDFS

- Agent: An individual, group, or app

- Local: On the same Solid pod.  These are not necessarily private.

- Remote: On a different Solid pod

- Descendant: A vocabulary cloned from an ancestor and changed or intended to be changed in some way

- Ancestral: A vocabulary with descendants
