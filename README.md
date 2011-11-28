jQuery Timepicker Addon
=======================

Use
---
- To use this plugin you must include jQuery and jQuery UI with datepicker and slider
- Include timepicker-addon script
- now use timepicker with $('#selector').datetimepicker() or $('#selector').timepicker()
- To run see demo.html

Contributing Code - Please Read!
--------------------------------
All code contributions and bug reports are much appreciated.  Please be sure to apply your fixes to the "dev" branch.

Example
--------------------------------
    <html>
    <head>
      <script type="text/javascript" src="http://code.jquery.com/jquery-1.7.1.min.js"></script>
      <script type="text/javascript" src="http://code.jquery.com/ui/1.8.16/jquery-ui.min.js"></script>
      <link rel="stylesheet" type="text/css" href="http://code.jquery.com/ui/1.8.16/themes/ui-lightness/jquery-ui.css" />
      <script type="text/javascript" src="jquery-ui-timepicker-addon.js"></script>

      <style type="text/css">
        /* css for timepicker */
        #ui-datepicker-div{ font-size: 80%; }
        .ui-timepicker-div .ui-widget-header { margin-bottom: 8px; }
        .ui-timepicker-div dl { text-align: left; }
        .ui-timepicker-div dl dt { height: 25px; }
        .ui-timepicker-div dl dd { margin: -25px 10px 10px 65px; }
        .ui-timepicker-div td { font-size: 90%; }
        .ui-tpicker-grid-label { background: none; border: none; margin: 0; padding: 0; }
      </style>

    </head>

    <script type="text/javascript">
      $('document').ready(function() {

        $("#date").datetimepicker({
          ampm: true,
          timeFormat: 'hh:mm TT'
        });

      });
    </script>

    <body>

      <input id="date">

    </body>
    </html>
