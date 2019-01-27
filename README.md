# IonicV4FontAwesome



##Instal

$ npm i @fortawesome/angular-fontawesome

$ npm i --save @fortawesome/fontawesome-svg-core

$ npm i --save @fortawesome/free-solid-svg-icons

##Integran en app.module.ts

import { FontAwesomeModule } from '@fortawesome/angular-fontawesome';
import { library } from '@fortawesome/fontawesome-svg-core';
import { faCoffee } from '@fortawesome/free-solid-svg-icons';

library.add(faCoffee);

y en imports añadir => FontAwesomeModule

##Integrar en home.module.ts

import { FontAwesomeModule } from '@fortawesome/angular-fontawesome';

y en imports añadir => FontAwesomeModule

##integrar en home.page.ts

import { faCoffee } from '@fortawesome/free-solid-svg-icons';

y en la clase =>   faCoffee = faCoffee;


##Uso en home.page.html

    <ion-list lines=full>
      <ion-item>
        Direct import <fa-icon [icon]="faCoffee" slot="end"></fa-icon>
      </ion-item>
      <ion-item>
        Big <fa-icon icon="graduation-cap"  slot="end"></fa-icon>
      </ion-item>
    </ion-list>


