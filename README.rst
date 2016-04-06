Volley -Vosign - Sign Language HTPP request
---------------------------------------

Volley instance using custom request and param

Instruction
=================

Here we go

1.
    add internet permission
    ::
        add android.permission.INTERNET to the app manifest



Example
=========
    The snippet below is a php script show how to accept request and post back to volley

        from php file

         $name = $_POST["name"];

          $j = array('name' =>$name);
          echo json_encode($j);


    Output is
    ::
        Droider
