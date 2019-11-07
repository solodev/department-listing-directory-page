# department-listing-directory-page
If you have multiple departments or directories in your organization, it’s important to create a single page that lists important info as well as links to separate pages.

## Tutorial
For detailed instruction's, view Solodev's [How to Create a Department Listing or Directory Page (Part 1)](https://www.solodev.com/blog/web-design/how-to-create-a-department-listing-or-directory-page-part-1.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/gwytsadj/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="container">
      <section class="quick-links departments paddingSection40">
        <div class="heading-wrapper">
          <h2 class="mt-5 mb-4"> LunarXP Departments</h2>
        </div><!-- .heading-wrapper -->
        <ul class="row">
          <li class="col-sm-12 col-md-6  col-lg-4  department">
            <a class="department-link" title="#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-building"></i></div>
                </div>
              <div class="col-xs-8 department-info">LunarXP Headquarters<span class="department-phone">123-456-7891</span></div>
            </div><!-- .row -->
           </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-commenting"></i></div>
                </div>
                <div class="col-xs-8 department-info">Communications<span class="department-phone">123.456.7891</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-flask"></i></div>
                </div>
                <div class="col-xs-8 department-info">Science Department<span class="department-phone">123.456.7891</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-cogs"></i></div>
                </div>
                <div class="col-xs-8 department-info">Engineering Department<span class="department-phone">123.456.7891</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-user"></i></div>
                </div>
                <div class="col-xs-8 department-info">Pilot Information<span class="department-phone"> 123.456.7891</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="h#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-space-shuttle"></i></div>
                </div>
                <div class="col-xs-8 department-info">Transportation<span class="department-phone">555.555.5555</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-user-md"></i></div>
                </div>
                <div class="col-xs-8 department-info">Medical Staff<span class="department-phone">123.456.7891</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="#" href="#">
              <div class="row">
                <div class="col-xs-4 department-icon">
                  <div class="icon-box text-center"><i class="fa fa-wrench"></i></div>
                </div>
                <div class="col-xs-8 department-info">Base Operations<span class="department-phone">123.456.7891</span></div>
              </div><!-- .row -->
            </a>
          </li>
          <li class="col-sm-12 col-md-6  col-lg-4  department"><a class="department-link" title="#" href="#">
            <div class="row">
              <div class="col-xs-4 department-icon">
                <div class="icon-box text-center"><i class="fa fa-university"></i></div>
              </div>
              <div class="col-xs-8 department-info">Space Studies<span class="department-phone">123.456.7891</span></div>
            </div><!-- .row -->
          </a>
        </li>
        </ul>
      </section><!-- .departments -->
    </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
```
