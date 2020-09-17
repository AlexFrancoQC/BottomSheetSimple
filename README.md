# BottomSheetSimple
BottomSheetSimple solo con xml


es un componente que se desliza hacia arriba desde la parte inferior de la pantalla para revelar más contenido. Puede encontrar información más detallada de la hoja inferior en las pautas de Google Material Design .



implementation 'com.android.support:design:28.0.0'




behavior_peekHeight: define la altura de la parte visible.
behaviour_hideable: define si la hoja inferior se puede ocultar deslizándola hacia abajo.


Vista de contenedor
Agregue CoordinatorLayout como la vista raíz. Luego, incluya la vista de la hoja inferior como elemento secundario directo de CoordinatorLayout . Los diseños app_bar y activity_bottom_sheet_content son algunas referencias de vista que no están relacionadas con la hoja inferior. Para que pueda reemplazarlos o eliminarlos.






![image](https://user-images.githubusercontent.com/64702836/93499815-d7371080-f8e9-11ea-86a4-75641d62831c.png)




![image](https://user-images.githubusercontent.com/64702836/93499854-e3bb6900-f8e9-11ea-88b3-fbdabfd7f998.png)




![image](https://user-images.githubusercontent.com/64702836/93499907-f766cf80-f8e9-11ea-9902-a4123af879ea.png)




![image](https://user-images.githubusercontent.com/64702836/93499963-0c436300-f8ea-11ea-804e-e236cb9f4135.png)




