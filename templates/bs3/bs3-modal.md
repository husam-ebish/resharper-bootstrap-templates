---
guid: 31ea2fce-0a20-4d6e-8849-a6a3f4c2dafa
type: Live
reformat: True
shortenReferences: True
categories: bootstrap 3
scopes: InHtmlLikeFile
parameterOrder: id, title, close, save
id-expression: constant("id")
title-expression: constant("Modal title")
close-expression: constant("Close")
save-expression: constant("Save")
---

# bs3-modal

Modal dialog

```
<a class="btn btn-primary" data-toggle="modal" href="#$id$">Trigger modal</a>
<div class="modal fade" id="$id$">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
                <h4 class="modal-title">$title$</h4>
            </div>
            <div class="modal-body">
                $END$
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">$close$</button>
                <button type="button" class="btn btn-primary">$save$</button>
            </div>
        </div>
    </div>
</div>
```
