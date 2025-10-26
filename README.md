
<!---<!DOCTYPE html>----->
<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>EduVerse - Login/Signup</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Lexend:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "primary": "#137fec",
                        "background-light": "#f6f7f8",
                        "background-dark": "#101922",
                    },
                    fontFamily: {
                        "display": ["Lexend", "sans-serif"]
                    },
                    borderRadius: {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings:
            'FILL' 0,
            'wght' 400,
            'GRAD' 0,
            'opsz' 24
        }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark font-display">
<div class="relative flex min-h-screen w-full flex-col items-center justify-center bg-background-light dark:bg-background-dark group/design-root overflow-x-hidden p-4 sm:p-6 lg:p-8">
<div class="layout-container flex h-full grow flex-col w-full max-w-4xl">
<div class="flex flex-col items-center justify-center w-full">
<div class="text-center mb-8">
<h1 class="text-primary dark:text-white tracking-light text-4xl font-bold leading-tight pb-2 pt-6 font-display">EduVerse</h1>
<p class="text-gray-600 dark:text-gray-300 text-base font-normal leading-normal font-display">Unlock Your Potential with EduVerse</p>
</div>
<div class="bg-white dark:bg-background-dark shadow-xl rounded-xl w-full p-6 sm:p-8 lg:p-10 border border-gray-200 dark:border-gray-700">
<div class="flex flex-col md:flex-row gap-8">
<!-- Login Section -->
<div class="w-full md:w-1/2 md:pr-8 md:border-r md:border-gray-200 dark:md:border-gray-700">
<div class="flex flex-col">
<div class="flex flex-wrap justify-between gap-3 p-4">
<div class="flex flex-col gap-1">
<p class="text-gray-800 dark:text-white tracking-light text-2xl font-bold leading-tight font-display">Welcome Back!</p>
<p class="text-gray-500 dark:text-gray-400 text-sm font-normal leading-normal font-display">Login to your account</p>
</div>
</div>
<form class="space-y-6 px-4">
<div class="flex flex-col">
<label class="text-gray-800 dark:text-gray-200 text-base font-medium leading-normal pb-2 font-display" for="login-email">Email/Username</label>
<input class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-gray-800 dark:text-white focus:outline-0 focus:ring-2 focus:ring-primary/50 border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-800 focus:border-primary h-12 placeholder:text-gray-400 dark:placeholder-gray-500 px-4 text-base font-normal leading-normal font-display" id="login-email" placeholder="Enter your email or username" type="text"/>
</div>
<div class="flex flex-col">
<label class="text-gray-800 dark:text-gray-200 text-base font-medium leading-normal pb-2 font-display" for="login-password">Password</label>
<input class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-gray-800 dark:text-white focus:outline-0 focus:ring-2 focus:ring-primary/50 border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-800 focus:border-primary h-12 placeholder:text-gray-400 dark:placeholder-gray-500 px-4 text-base font-normal leading-normal font-display" id="login-password" placeholder="Enter your password" type="password"/>
</div>
<div class="flex items-center justify-between">
<a class="text-sm font-medium text-primary hover:underline dark:text-primary/90 font-display" href="#">Forgot Password?</a>
</div>

<a href="./student_homepage_with-to-do/"
   class="block w-full text-center bg-primary text-white font-bold py-3 px-4 rounded-lg hover:bg-primary/90 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-primary font-display transition-colors duration-300">
   Login
</a>

</form>
<div class="flex items-center my-6 px-4">
<div class="flex-grow border-t border-gray-300 dark:border-gray-600"></div>
<span class="flex-shrink mx-4 text-gray-500 dark:text-gray-400 font-display text-sm">Or continue with</span>
<div class="flex-grow border-t border-gray-300 dark:border-gray-600"></div>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 px-4">
<button class="flex items-center justify-center gap-2 w-full bg-white dark:bg-gray-800 text-gray-700 dark:text-gray-200 font-semibold py-2 px-4 border border-gray-300 dark:border-gray-600 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 transition-colors duration-300">
<img alt="Google logo" class="h-5 w-5" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAyRoX03Ip6xBDjAUYCSSNR8Ws84AQyVTaO28LhBDDcHNLcycACpMIFPgJj_z0cBuBogOE_Dx_McBFoRzjqi4yE2ffIIg2zd0Hh8um2JL7a9FMdo6oeuQbk6B8bV0Z3Y-8W5Sle4xvs4lu97KdHYC6dCanq18ML_8vv63bnPrFxpJc2yPeAS3n2vJ2nR50yxR-6x9-7I1rtkFEwdLT_VLtGn956lmSBgWNY6F5b7ykAteh1mjr7GrKSBzhi1S3stDbh5MEhMT_CBMJ9"/>
                                        Google
                                    </button>
<button class="flex items-center justify-center gap-2 w-full bg-white dark:bg-gray-800 text-gray-700 dark:text-gray-200 font-semibold py-2 px-4 border border-gray-300 dark:border-gray-600 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 transition-colors duration-300">
<img alt="Facebook logo" class="h-5 w-5" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAaXqd8bbZ_qvFIbKeYBuhp0mB4twDrx9kQQX7xaxDOKaougQT_giEHnXe7wG0UAGIpLDNcZbaqw9vo74kG2nXzNL0_75Bp9pPpihgqPH1F2X4hDZ0UQOERuHXCqKTLaPYC3OJp_R4lU_SVLmB_fJUHZL7jPD661w0pUi0zctvs_yrWc9tKTwxZt1syqhAFeyzPSLosBxLsoyuK5de_3kn36bCVSnVdmtM3jt6JWxRECMnEeSN6QN8amDIpNMuDNgCX2syXwmVklc5A"/>
                                        Facebook
                                    </button>
</div>
</div>
</div>
<!-- Signup Section -->
<div class="w-full md:w-1/2 md:pl-8">
<div class="flex flex-col">
<div class="flex flex-wrap justify-between gap-3 p-4">
<div class="flex flex-col gap-1">
<p class="text-gray-800 dark:text-white tracking-light text-2xl font-bold leading-tight font-display">New to EduVerse?</p>
<p class="text-gray-500 dark:text-gray-400 text-sm font-normal leading-normal font-display">Create an account</p>
</div>
</div>
<form class="space-y-6 px-4">
<div class="flex flex-col">
<label class="text-gray-800 dark:text-gray-200 text-base font-medium leading-normal pb-2 font-display" for="signup-name">Name</label>
<input class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-gray-800 dark:text-white focus:outline-0 focus:ring-2 focus:ring-primary/50 border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-800 focus:border-primary h-12 placeholder:text-gray-400 dark:placeholder-gray-500 px-4 text-base font-normal leading-normal font-display" id="signup-name" placeholder="Enter your full name" type="text"/>
</div>
<div class="flex flex-col">
<label class="text-gray-800 dark:text-gray-200 text-base font-medium leading-normal pb-2 font-display" for="signup-email">Email</label>
<input class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-gray-800 dark:text-white focus:outline-0 focus:ring-2 focus:ring-primary/50 border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-800 focus:border-primary h-12 placeholder:text-gray-400 dark:placeholder-gray-500 px-4 text-base font-normal leading-normal font-display" id="signup-email" placeholder="Enter your email" type="email"/>
</div>
<div class="flex flex-col">
<label class="text-gray-800 dark:text-gray-200 text-base font-medium leading-normal pb-2 font-display" for="signup-password">Password</label>
<input class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-gray-800 dark:text-white focus:outline-0 focus:ring-2 focus:ring-primary/50 border border-gray-300 dark:border-gray-600 bg-white dark:bg-gray-800 focus:border-primary h-12 placeholder:text-gray-400 dark:placeholder-gray-500 px-4 text-base font-normal leading-normal font-display" id="signup-password" placeholder="Create a password" type="password"/>
</div>
<div class="flex items-start">
<div class="flex items-center h-5">
<input aria-describedby="terms-description" class="focus:ring-primary h-4 w-4 text-primary border-gray-300 rounded" id="terms" name="terms" type="checkbox"/>
</div>
<div class="ml-3 text-sm">
<label class="font-medium text-gray-700 dark:text-gray-300 font-display" for="terms">I agree to the <a class="text-primary hover:underline" href="#">Terms &amp; Conditions</a></label>
</div>
</div>
<button class="w-full bg-[#F5A623] text-white font-bold py-3 px-4 rounded-lg hover:bg-[#F5A623]/90 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-[#F5A623] font-display transition-colors duration-300">Sign Up</button>
</form>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</body></html>
