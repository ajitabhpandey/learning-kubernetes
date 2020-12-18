# Third party powertools for kubernetes

### kubectx

To install kubectx. Tools like kubens also gets installed
`brew install kubectx`

Displays all available contexts. Useful if you are working in a multicluster environment.
`kubectx`


Lists all available namespaces in the current context
`kubens`

Change the active namespace in the current context. This helps if lots of opertions are to be done over a specific operation.
`kubens mongo-express`
