# Kanban-jQuery
Kanban Board jQuery Plugin

# Example

Example of the HTML element
```html
  <div id="kanban"></div>
```

Example of the javascript call to create a Kanban Board
```js
  $('#kanban').kanban({
        titles: ['Task' , 'Estimate' , 'Complete' , 'Invoiced' , 'Paid'],
        colours: ['#00aaff','#ff921d','#00ff40','#ffe54b','#8454ff'],
        items: [
            {
                id: 1,
                title: 'Test',
                block: 'Task',
                link: '[URL]',
                link_text: 'TEST001',
                footer: '<i class="ion-md-chatboxes"></i> 1 <div class="pull-right"><i class="ion-md-checkbox"></i> 1/4</div>'
            },
            {
                id: 2,
                title: 'Test 2',
                block: 'Estimate',
                footer: '<i class="ion-md-chatboxes"></i> 1 <div class="pull-right"><i class="ion-md-checkbox"></i> 1/4</div>'
            },
            {
                id: 3,
                title: 'Test 3',
                block: 'Estimate',
                footer: '<i class="ion-md-chatboxes"></i> 1 <div class="pull-right"><i class="ion-md-checkbox"></i> 1/4</div>'
            },
            {
                id: 4,
                title: 'Test 5',
                block: 'Estimate',
                footer: '<i class="ion-md-chatboxes"></i> 1 <div class="pull-right"><i class="ion-md-checkbox"></i> 1/4</div>'
            },
            {
                id: 5,
                title: 'Test 5',
                block: 'Estimate',
                footer: '<i class="ion-md-chatboxes"></i> 1 <div class="pull-right"><i class="ion-md-checkbox"></i> 1/4</div>'
            },
        ]
    });
```
