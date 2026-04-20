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

# Table
        <table id="example" class="display">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Position</th>
                    <th>Office</th>
                    <th>Age</th>
                    <th>Start date</th>
                    <th>Salary</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Tiger Nixon</td>
                    <td>System Architect</td>
                    <td>Edinburgh</td>
                    <td>61</td>
                    <td>2011-04-25</td>
                    <td>$320,800</td>
                </tr>        
            </tbody>
            <tfoot>
                <tr>
                    <th>Name</th>
                    <th>Position</th>
                    <th>Office</th>
                    <th>Age</th>
                    <th>Start date</th>
                    <th>Salary</th>
                </tr>
            </tfoot>
        </table>


    ## CSS
    https://cdn.datatables.net/2.3.7/css/dataTables.dataTables.css
    https://cdn.datatables.net/buttons/3.2.6/css/buttons.dataTables.css

    
    ## JS
    new DataTable('#example', {
    layout: {
        topStart: {
            buttons: ['copyHtml5', 'excelHtml5', 'csvHtml5', 'pdfHtml5']
            }
        }
    });

    https://datatables.net/extensions/buttons/examples/html5/simple.html
    https://code.jquery.com/jquery-3.7.1.js
    https://cdn.datatables.net/2.3.7/js/dataTables.js
    https://cdn.datatables.net/buttons/3.2.6/js/dataTables.buttons.js
    https://cdn.datatables.net/buttons/3.2.6/js/buttons.dataTables.js
    https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js
    https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.2.7/pdfmake.min.js
    https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.2.7/vfs_fonts.js
    
    
    
