# go-utils
utils for gene ontology data manipulation


    Usage:   go-utils <command> <arguments>
    Version: 0.0.1-r1-dirty

    Command:
          -- OBO manipulation
             alt      parse alt_id/id map  .
             name     parse GO names.
             map      parse GO term hierarchical relationship [is-a]

          -- GO slim manipulation
             update   update to the latest OBO.
             internal traversal GO hierarchical tree to include the internal node.
             level    get GO terms of specify level in hierarchical tree.

          -- misc
             path     traversal GO hierarchical tree to get GO path.

