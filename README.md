# ConstraintLayOut
Constraint Layout


1.Constraint layout was introduced to solve alignment and performance issues of previous layouts.

2.It is similar to relative layout in that widgets are positioned relative to siblings or parent.

3.But it is more flexible meaning it allows you to easily align widgets as required 

4  You can create layouts fast with improved runtime performance.
Constraint Layout Unique Features
Speed of development, performance of layouts, responsive layouts are some of the features of constraint layout.

1.One of the issues with other layouts is increase in hierarchy levels.Nesting layouts is a problem.

2.Constrain layout allows you to build layouts which behave in terms of display as designed on the devices with different screen sizes.

3.ability to set the size of widget to match to position constraints.

4.easy to use android layout editor tool which was re-created to support constraint layout.

Constraints :


1.Constraints determine the position of a widget in layout relative to other widgets, guideline or parent.

2.If you add a widget to layout without any constraints, it will be positioned top left corner of the screen.(we can supress warning by adding  tools:ignore="MissingConstraints"attribute ).

constraint right corner
          
          
          app:layout_constraintRight_toRightOf="parent"
 
 constraint bottom corner
   
   
          app:layout_constraintBottom_toBottomOf="parent"

constraint top corner | without  constraints(position same in this case)
    
    
          app:layout_constraintTop_toTopOf="parent"

constraint only  left corner | without  constraints(position same in this case) 

          app:layout_constraintLeft_toLeftOf="parent"

center :

          app:layout_constraintBottom_toBottomOf="parent"
          app:layout_constraintLeft_toLeftOf="parent"
          app:layout_constraintRight_toRightOf="parent"
          app:layout_constraintTop_toTopOf="parent"

bottom right :
         app:layout_constraintBottom_toBottomOf="parent"
         app:layout_constraintRight_toRightOf="parent
