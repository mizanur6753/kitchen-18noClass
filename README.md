# kitchen-18noClass
kitchen-18noClass


php artisan make:controller AboutController 

php artisan make:model Todo -m

php artisan migrate 



@yield('title')
 @section('title','Todos-list')

@yield('content') 
 @extends('layouts.app')

@section('content') 
 @endsection

@csrf 
======================
======================



http://kitchen.test
===================

https://github.com/laravel/ui

composer require laravel/ui
npm install
npm run dev / npm run build 



{{ asset('frontend/ ...  ') }}
{{ asset('backend/ ... ') }}



php artisan make:controller Admin/DashboardController 

Route::group(['prefix' => 'admin', 'middleware' => 'auth'], function(){


}); 


      @if (Request::is('admin*'))
        @include('layouts.partial.sidebar')
      @endif



<form action="{{ route('logout') }}"></form> 

php artisan route:list


Logout-system
============= 
            <a href="{{ route('logout') }}" onclick="event.preventDefault();document.getElementById('logout-form').submit();" class="nav-link text-body font-weight-bold px-0">
              <i class="fa fa-user me-sm-1"></i>
              <span class="d-sm-inline d-none">Log out</span>

              <form id="logout-form" action="{{ route('logout') }}" method="POST" style="display: none" >
                @csrf
              </form>

            </a>


<li><a href="{{ route('login') }}">Login</a></li>



