 <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
      html,
    body {
        height: 100%;
        }

        body {
        display: -ms-flexbox;
        display: flex;
        -ms-flex-align: center;
        align-items: center;
        padding-top: 40px;
        padding-bottom: 40px;
        background-color: #f5f5f5;
        }

        .form-signin {
        width: 100%;
        max-width: 420px;
        padding: 15px;
        margin: auto;
        }

        .form-label-group {
        position: relative;
        margin-bottom: 1rem;
        }

        .form-label-group > input,
        .form-label-group > label {
        height: 3.125rem;
        padding: .75rem;
        }

        .form-label-group > label {
        position: absolute;
        top: 0;
        left: 0;
        display: block;
        width: 100%;
        margin-bottom: 0; /* Override default `<label>` margin */
        line-height: 1.5;
        color: #495057;
        pointer-events: none;
        cursor: text; /* Match the input under the label */
        border: 1px solid transparent;
        border-radius: .25rem;
        transition: all .1s ease-in-out;
        }

        .form-label-group input::-webkit-input-placeholder {
        color: transparent;
        }

        .form-label-group input:-ms-input-placeholder {
        color: transparent;
        }

        .form-label-group input::-ms-input-placeholder {
        color: transparent;
        }

        .form-label-group input::-moz-placeholder {
        color: transparent;
        }

        .form-label-group input::placeholder {
        color: transparent;
        }

        .form-label-group input:not(:placeholder-shown) {
        padding-top: 1.25rem;
        padding-bottom: .25rem;
        }

        .form-label-group input:not(:placeholder-shown) ~ label {
        padding-top: .25rem;
        padding-bottom: .25rem;
        font-size: 12px;
        color: #777;
        }

        /* Fallback for Edge
        -------------------------------------------------- */
        @supports (-ms-ime-align: auto) {
        .form-label-group > label {
            display: none;
        }
        .form-label-group input::-ms-input-placeholder {
            color: #777;
        }
        }

        /* Fallback for IE
        -------------------------------------------------- */
        @media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
        .form-label-group > label {
            display: none;
        }
        .form-label-group input:-ms-input-placeholder {
            color: #777;
        }
        }
    </style>
    <form class="form-signin">
        <div class="text-center mb-4">
            <img class="mb-4" src="/docs/4.4/assets/brand/bootstrap-solid.svg" alt="" width="72" height="72">
            <h1 class="h3 mb-3 font-weight-normal">Sign Up </h1>
            <p>Make online classrooms <code>:Virtual online Conferance classes</code> Assignments and Notes. <a href="#">Works in any platfrom any browser. No forceful Apps.</a></p>
        </div>

        <div class="form-label-group">
            <input type="email" id="inputUsername" class="form-control" placeholder="Username" required >
            <label for="inputUsername">username</label>
        </div>
        <div class="form-label-group">
            <input type="email" id="inputEmail" class="form-control" placeholder="Email address" required >
            <label for="inputEmail">Email</label>
        </div>

        <div class="form-label-group">
            <input type="password" id="inputPassword" class="form-control" placeholder="Password" required>
            <label for="inputPassword">Password</label>
        </div>

        <div class="checkbox mb-3">
            <label>
            <input type="checkbox" value="remember-me"> Agree Terms and Conditions
            </label>
        </div>
        <button class="btn btn-lg btn-primary btn-block" type="submit">Sign Up</button>
        <p class="mt-5 mb-3 text-muted text-center">&copy; 2020</p>
    </form>
 