# CDS Views

## Display a CDS View in SALV 
```abap
SELECT * FROM ZDENEME_MM
         INTO TABLE @DATA(lt_data).


cl_salv_gui_table_ida=>create_for_cds_view( 'ZDENEME_MM' )->fullscreen( )->display( ). 
```