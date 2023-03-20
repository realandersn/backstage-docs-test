# Graphviz

You can use Graphviz definitions to render graphs inline. The supported graphviz commands are `dot`, `neato`, `fdp`, `sfdp`, `twopi`, and `circo`. For more information, see the [official documentation](https://graphviz.gitlab.io/documentation/).

!!! example

    ```
    {% dot attack_plan.svg
        digraph G {
            rankdir=LR
            Earth [peripheries=2]
            Mars
            Earth -> Mars
        }
    %}
    
    ```
    

will render:
    
{% dot attack_plan.svg
    digraph G {
        rankdir=LR
        Earth [peripheries=2]
        Mars
        Earth -> Mars
    }
%}
    
