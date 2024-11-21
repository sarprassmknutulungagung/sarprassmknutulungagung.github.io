<html>
<head>
    <title>Inventory App</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body class="bg-gray-200 flex items-center justify-center min-h-screen">
    <div class="bg-white p-8 rounded-lg shadow-lg w-96">
        <h1 class="text-center text-2xl font-semibold mb-6">Inventory App</h1>
        <form>
            <div class="mb-4">
                <label class="block relative">
                    <span class="absolute inset-y-0 left-0 flex items-center pl-3">
                        <i class="fas fa-user text-gray-400"></i>
                    </span>
                    <input type="text" placeholder="Username" class="pl-10 pr-4 py-2 w-full border rounded-lg focus:outline-none focus:ring-2 focus:ring-green-500">
                </label>
            </div>
            <div class="mb-6">
                <label class="block relative">
                    <span class="absolute inset-y-0 left-0 flex items-center pl-3">
                        <i class="fas fa-lock text-gray-400"></i>
                    </span>
                    <input type="password" placeholder="Password" class="pl-10 pr-4 py-2 w-full border rounded-lg focus:outline-none focus:ring-2 focus:ring-green-500">
                </label>
            </div>
            <div class="text-center">
                <button type="submit" class="bg-green-500 text-white py-2 px-4 rounded-lg hover:bg-green-600 focus:outline-none focus:ring-2 focus:ring-green-500">Log in</button>
            </div>
        </form>
        <div class="text-center mt-4">
            <a href="https://smknu-tulungagung.sch.id" class="text-green-500 text-sm">https://smknu-tulungagung.sch.id ©2024</a>
        </div>
    </div>
</body>
</html>
