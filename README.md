# ngDemo3-bucket-list

# 1. Start new ng5 project
ng new bucketlist --style=scss --routing

# 2. Create new components
ng generate component home
ng g c about

# 3. Update app.component.html to create simple nav menu

# 4. Crate basic form and styling
Update the following files:
- home.component.html
- home.component.scss
- styles.sccs

# 5. Add itemCount property on home component and display it on home page using INTERPOLATION
{{ itemCount }}

# 6. Add btntext property on home component and display it on home page using PROPERTY BINDING
[value]="btnText"

# 7. Add goalText property on home component and display it on home page using TWO-WAY DATA BINDING
- First, need to import FormsModule on app.module.ts
[(ngModel)]="goalText"

# 8. Save user entered data using EVENT BINDING and display on screen
(click)="addItem()"

<p class="life-container" *ngFor="let goal of goals">
  {{ goal }}
</p>

# 9. Install angular animations library
npm install @angular/animations@latest --save

# 10. Add animations for elements added to DOM

# 11. Add animations for elements removed from DOM

# 12. Routing HOME and ABOUT
 