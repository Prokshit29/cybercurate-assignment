# cybercurate-assignment
Developed a staff profile form and screen
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Staff Profile Create</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 p-6">
  <div class="max-w-5xl mx-auto bg-white p-6 rounded-xl shadow-xl">
    <h2 class="text-2xl font-bold mb-4">Staff Profile Create</h2>

    <form class="space-y-6">
      <!-- Tabs -->
      <div class="flex border-b">
        <button type="button" class="py-2 px-4 border-b-2 border-blue-500 font-semibold text-blue-600">Profile</button>
        <button type="button" class="py-2 px-4 text-gray-500">Related Information</button>
      </div>

      <!-- Profile Section -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <label class="flex items-center space-x-2 col-span-2">
          <input type="checkbox" class="form-checkbox">
          <span>Enable Email Two Factor Authentication</span>
        </label>

        <div>
          <label class="text-sm font-medium">Staff Code *</label>
          <input type="text" class="w-full p-2 border rounded" required>
        </div>

        <div>
          <label class="text-sm font-medium">First Name *</label>
          <input type="text" class="w-full p-2 border rounded" value="Ananya" required>
        </div>

        <div>
          <label class="text-sm font-medium">Last Name *</label>
          <input type="text" class="w-full p-2 border rounded" value="Sharma" required>
        </div>

        <div>
          <label class="text-sm font-medium">Gender</label>
          <select class="w-full p-2 border rounded">
            <option>None selected</option>
            <option>Female</option>
            <option>Male</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Birthday</label>
          <input type="date" class="w-full p-2 border rounded">
        </div>

        <div>
          <label class="text-sm font-medium">Email *</label>
          <input type="email" class="w-full p-2 border rounded" value="talent@cybercurate.com" required>
        </div>

        <div>
          <label class="text-sm font-medium">Phone</label>
          <input type="text" class="w-full p-2 border rounded">
        </div>

        <div>
          <label class="text-sm font-medium">Workplace</label>
          <select class="w-full p-2 border rounded">
            <option>None selected</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Status *</label>
          <select class="w-full p-2 border rounded">
            <option>Working</option>
            <option>On Leave</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Job Position</label>
          <select class="w-full p-2 border rounded">
            <option>None selected</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Direct Manager</label>
          <select class="w-full p-2 border rounded">
            <option>None selected</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Role</label>
          <input type="text" class="w-full p-2 border rounded" value="Employee">
        </div>

        <div>
          <label class="text-sm font-medium">Academic Level</label>
          <select class="w-full p-2 border rounded">
            <option>Not required</option>
            <option>Graduate</option>
            <option>Post-Graduate</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Hourly Rate</label>
          <input type="number" class="w-full p-2 border rounded" value="0.00">
        </div>

        <div>
          <label class="text-sm font-medium">Default Language</label>
          <select class="w-full p-2 border rounded">
            <option>System Default</option>
            <option>English</option>
          </select>
        </div>

        <div>
          <label class="text-sm font-medium">Direction</label>
          <select class="w-full p-2 border rounded">
            <option>System Default</option>
          </select>
        </div>

        <div class="col-span-1">
          <label class="text-sm font-medium">Email Signature</label>
          <textarea class="w-full p-2 border rounded"></textarea>
        </div>

        <div class="col-span-1">
          <label class="text-sm font-medium">Other Information</label>
          <textarea class="w-full p-2 border rounded"></textarea>
        </div>

        <div class="col-span-1">
          <label class="text-sm font-medium">Twilio Phone Number</label>
          <input type="text" class="w-full p-2 border rounded">
        </div>

        <div class="col-span-1">
          <label class="text-sm font-medium">Is Twilio Number WhatsApp Enabled</label>
          <select class="w-full p-2 border rounded">
            <option>None selected</option>
          </select>
        </div>

        <div class="col-span-2">
          <label class="text-sm font-medium">Password *</label>
          <input type="password" class="w-full p-2 border rounded" required>
          <p class="text-xs text-gray-500">Note: If you populate this field, the password will be changed on this member.</p>
        </div>
      </div>

      <!-- Buttons -->
      <div class="flex justify-end gap-4 pt-6">
        <button type="button" class="px-4 py-2 border rounded hover:bg-gray-100">Close</button>
        <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">Save</button>
      </div>
    </form>
  </div>
</body>
</html>
