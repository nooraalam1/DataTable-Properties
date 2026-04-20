# DataTable-Properties

## Page Size & Pagination
    new DataTable('#facility', {
        pageLength: 10,
        lengthMenu: [5, 10, 25, 50],
        pagingType: "simple_numbers"
    });
    
    Options:
        pageLength → default rows per page
        lengthMenu → dropdown values
        pagingType →
        "simple"
        "simple_numbers"
        "full"
        "full_numbers"
        
## Sorting
    new DataTable('#facility', {
        ordering: true,
        order: [[0, 'asc']]
    });

## Searching / Filtering
    new DataTable('#facility', {
        searching: true
    });

## DOM Layout Control
    new DataTable('#facility', {
        dom: 'lfrtip'
    });
## Buttons

    new DataTable('#facility', {
        dom: 'Bfrtip',
        buttons: ['copy', 'csv', 'excel', 'pdf', 'print']
    });

    
