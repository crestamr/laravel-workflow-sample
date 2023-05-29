# Laravel Workflow Sample App

This is a sample Laravel 10 application with example workflows that you can run inside a GitHub codespace.

### Step 1
Run the migrations to create the necessary database tables.

```bash
php artisan migrate
```

### Step 2
Start the queue worker. This will enable the processing of workflows and activities.

```bash
php artisan queue:work
```

### Step 3
Create a new terminal window.

<img src="https://user-images.githubusercontent.com/1130888/233666917-029247c7-9e6c-46de-b304-27473fd34517.png" alt="image" width="200">

### Step 4
Start the example workflow inside the new terminal window.

```bash
php artisan workflow
```

### Step 5
You can view the waterline dashboard via the mapped port.

<img src="https://user-images.githubusercontent.com/1130888/233668485-b988e336-0462-4bbc-bb77-78c73df363b4.png" alt="image" width="500">

Add `/waterline/dashboard` to the URL e.g. `https://[your-project-name]/waterline/dashboard`

<img src="https://user-images.githubusercontent.com/1130888/233669600-3340ada6-5f73-4602-8d82-a81a9d43f883.png" alt="image" width="600">

That's it! You can now create and test workflows.
