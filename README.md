#route-protection

USE: 

    <div>
       <switch>

          <PublicRoute
            exact 
            path='/login' 
            component={ loginComponent }
            isAutenticated={ [true or false] }/>
 
          <PrivateRoute
            exact
            path='/app'
            component={ AppComponent } 
            isAutenticated={ [true or false] }/>

       </switch>
    </div> 


     