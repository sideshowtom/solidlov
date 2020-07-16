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

- An agent maintains a vocabulary for followers by hosting it on a pod and makes it available for copying, term searches and sparql queries.  

- An agent searches for a vocabulary term based on key words and/or app context, for use in autocomplete on form filling and creation.  Local, remote, descendant and ancestral vocabularies are searched in an order specified by search configuration.

- An agent creates or reuses a search configuration that specifies ordering of local, remote, descendant, and ancestral vocabularies for search

- An agent creates a descendant vocabulary by copying an ancestral vocabulary and making changes to it.  Descendant and ancestral vocabularies can be either local or remote.

- An agent that uses a vocabulary, or a class or property in a vocabulary, follows updates to the vocabulary, class or property.  In the case of classes and properties, the agent is given a choice of following all or some base classes or properties, and if some of those bases are in prerequisite vocabularies then the agent is given a choice of which of those bases and vocabularies are included in the follow process.  In the case of following an entire vocabulary, the agent is given a choice of which prerequisite vocabularies to include when following.

- An agent maintains a vocabulary, class, or property and sends information about updates to followers

- An agent that maintains a vocabulary, class or property follows updates to ancestral vocabularies, classes or properties

- An agent that maintains a vocabulary, class or property follows updates to descendant vocabularies, classes or properties

- An agent restricts access to a vocabulary to certain persons or groups

- An agent compares one vocabulary to another by measures such as equivalence, similarity, scope, structure, usage, provenance or fitness for purpose.

- An agent collects local vocabularies and optimizes them for search efficiency

- An agent sets or gets a form or html template associated with a vocabulary to be sent to followers when the vocabulary is updated.  The form or template will have boilerplate and also fields for the changed items.

- An agent sets or gets a form or html template associated with a class or property in a vocabulary to be sent to followers when the the class or property is updated. The form or template will have boilerplate that includes information about the vocabulary and also fields for the changed items.


## Terms

- Agent: An individual, group, or app
- Ancestral: A vocabulary with descendants
- Descendant: A vocabulary cloned from an ancestor and changed or intended to be changed in some way
- Local: On the same Solid pod.  These are not necessarily private.
- Prerequisite: A vocabulary that is included or imported in a dependent vocabulary
- Remote: On a different Solid pod
- Restrict: To specify access according to Solid protocols
- Follow: To get notifications according to ActivityPub protocols
- Vocabulary: An ontology in OWL or RDFS
