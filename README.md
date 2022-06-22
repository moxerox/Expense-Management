<h5>Deployment</h5>
    <ol>
        <li>
            Run <code>cp .env.example .env</code> file to copy example file to <code>.env</code> <br>Then edit your <code>.env</code> file with
            DB credentials and other settings.
        </li>
        <li>Run <code>composer install</code> command</li>
        <li>
            Run <code>php artisan migrate --seed</code> command. <br>
            Notice: seed is important, because it will create the first admin
            user for you.
        </li>
        <li>Run <code>php artisan key:generate</code> command.</li>
        <li>Run <code>npm install</code></li>
        <li>Run <code>npm run dev</code></li>
        <li>
            If you have file/photo fields, run
            <code>php artisan storage:link</code> command.
        </li>
        <li>
            Laravel Sanctum for API Auth: If you are using custom hostname for
            project other than localhost make sure that value of
            <code>SANCTUM_STATEFUL_DOMAINS</code> variable in
            <code>.env</code> file is the same as your hostname in browser.
            Example: <code>SANCTUM_STATEFUL_DOMAINS=myproject.test</code>
        </li>
    </ol>
    <p>And that's it, go to your domain and login:</p> 
    <hr></hr>
    <h3>
        Default credentials
    </h3> 
    Username: <code>admin@admin.com</code><br>
    Password: <code>password</code></div> <p>
    For more information, potential errors and related links, you can read
    <a href="https://linktr.ee/malfaghi" target="_blank" class="text-primary">
        Contact Me Here
    </a>
</p>
        
