# Fix-Error-Screen-PDF-LIST-SuiteCrm
This code fix the error when suitecrm has a lot of pdfs in the list
tutorial:
1 - Add this code inside of detailviewdefs.php in module that u need to fix:<br>
<p>'includes' =>
                array (
                    0 =>
                    array (
                        'file' => 'custom/scripts/fixerrorscreen.js',
                    )
					
					
					
                ),</p>
2 - Add fixerrorscreen.js in your custom/scripts
