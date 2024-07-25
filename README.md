<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Responsive Table/List</title>  
    <script src="https://cdn.tailwindcss.com"></script>  
</head>  
<body class="bg-gray-100 p-6">  
    <div class="container mx-auto">  
        <h1 class="text-2xl font-bold mb-4 text-center underline">TABLE</h1>  

        <!-- Table for large screens -->  
        <table class="hidden lg:table w-full border-collapse">  
            <thead>  
                <tr class="bg-green-500 text-white">  
                    <th class="py-2 px-4 border">FIRST NAME</th>  
                    <th class="py-2 px-4 border">LAST NAME</th>  
                    <th class="py-2 px-4 border">AGE</th>  
                </tr>  
            </thead>  
            <tbody>  
                <tr class="bg-red-500 hover:underline">  
                    <td class="py-2 px-4 border">Accrea</td>  
                    <td class="py-2 px-4 border">Fantasy</td>  
                    <td class="py-2 px-4 border">20</td>  
                </tr>  
                <tr class="bg-red-500 hover:underline">  
                    <td class="py-2 px-4 border">Hess</td>  
                    <td class="py-2 px-4 border">Ceana</td>  
                    <td class="py-2 px-4 border">19</td>  
                </tr>  
            </tbody>  
        </table>  

        <!-- List for small screens -->  
        <div class="lg:hidden">  
            <div class="bg-orange-500 hover:underline shadow-md rounded-lg p-4 mb-4">  
                <div class="flex justify-between mb-2">  
                    <span class="font-bold">FIRST NAME:</span>  
                    <span>Accrea</span>  
                </div>  
                <div class="flex justify-between mb-2">  
                    <span class="font-bold">LAST NAME:</span>  
                    <span>Fantasy</span>  
                </div>  
                <div class="flex justify-between mb-2">  
                    <span class="font-bold">AGE:</span>  
                    <span>20</span>  
                </div>  
            </div>  

            <div class="bg-orange-500 hover:underline shadow-md rounded-lg p-4">  
                <div class="flex justify-between mb-2">  
                    <span class="font-bold">FIRST NAME:</span>  
                    <span>Hess</span>  
                </div>  
                <div class="flex justify-between mb-2">  
                    <span class="font-bold">LAST NAME:</span>  
                    <span>Ceana</span>  
                </div>  
                <div class="flex justify-between mb-2">  
                    <span class="font-bold">AGE:</span>  
                    <span>19</span>  
                </div>  
            </div>  
        </div>  
    </div>  
</body>  
</html>
