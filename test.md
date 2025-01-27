# K-Component Layout

**Descripción:**
Este componente contiene el diseño completo con el nombre de la aplicación, título, plantillas para encabezado, ayuda, barra lateral, contenido y una tabla paginada.

## Uso

```html
<k-layout [appName]="'Proyecto Base'" [pageTitle]="'Administración de personas.'" [headerTemplate]="headerTemplate"
   (logout)="logout()" [disableLinkHome]="false" [sidebarTemplate]="sidebarTemplate" [disableLoading]="false"
   [helpTemplate]="helpTemplate" [audit]="false">
   <ng-container *ngTemplateOutlet="mycontent">
   </ng-container>
</k-layout>
