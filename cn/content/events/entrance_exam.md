+++
date = "2015-04-25T11:11:11+08:00"
draft = false
title = "Entrance Exam"
day = "08"
month = "Aug"
location = "Shanghai Fudan University"
description = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean dictum varius ipsum"
time = "12pm"
type = "events"

+++
<div class='row'>
  <div class="col-sm-4">
    <div class="sidebar">
      <div class="col-sm-12">
        <div class='page-header page-header-with-icon'>
          <i class='fa fa-clock-o'></i>
          <h2>Sat 8th August 2015</h2>
        </div>
        <h3 class="program">12:45-13:30
          <br>13:30-16:30</h3>
        <h4 class="position">Shanghai Fudan University</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean dictum varius ipsum,</p>
        <button type="button" class="btn btn-primary" data-toggle="modal" data-target=".contact-form">Register for Event</button>
        <div class="modal fade contact-form" tabindex="-1" role="dialog" aria-hidden="true">
          <div class="modal-dialog modal-lg">
            <div class="modal-content">
              <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="gridSystemModalLabel">Register For This Event</h4>
              </div>
              <div class="modal-body">
                <form class="form form-validation form-contact" method="post" novalidate="novalidate">
                  <div class="row">
                    <div class="col-sm-12">
                      <div class="alert alert-success form-contact-success hidden">Thanks! Your message has been successfully sent!</div>
                      <div class="alert alert-danger form-contact-error hidden">Ooops! There was an error sending your message.</div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-12">
                      <div class="form-group control-group">
                        <input class="form-control" data-rule-required="true" name="id" type="text" value="EVENT0001" readonly="">
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-6">
                      <div class="form-group control-group">
                        <input class="form-control" data-rule-required="true" name="name" placeholder="Name" type="text">
                        <!-- / this field is required for simple anti spam function, don't remove it! -->
                        <input class="form-control" name="human" placeholder="Are you human?" style="display: none;" type="text">
                      </div>
                    </div>
                    <div class="col-sm-6">
                      <div class="form-group control-group">
                        <input class="form-control" data-rule-email="true" data-rule-required="true" name="email" placeholder="E-Mail" type="email">
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-12">
                      <div class="form-group control-group">
                        <textarea class="form-control" data-rule-required="true" name="message" placeholder="Your message..."></textarea>
                      </div>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-12">
                      <button class="btn btn-contrast btn-block form-contact-submit" data-loading-text="&lt;i class='fa fa fa-refresh fa fa fa-spin'&gt;&lt;/i&gt; Sending..." type="submit">Send message</button>
                    </div>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class='col-sm-8'>
    <div class='text-boxes'>
      <div class='row text-box'>
        <div class='col-sm-12'>
          <div class='page-header page-header-with-icon'>
            <i class='fa fa-info-circle '></i>
            <h2>BI Norwegian Business School- Fudan University MBA Program Entrance Exam</h2>
          </div>
          <p>The BI-Fudan MBA program is offered in partnership by BI Norwegian Business School and School of Management at Fudan University. Building on one of the first joint programs in China, established in 1996, the BI-Fudan MBA program provides the best of two worlds:</p>
          <p><strong>*Courses entirely in English, which combines the best teaching resources of BI and Fudan</strong>
          </p>
          <p class="no-mg-b"><strong>*International modules with top notch universities around the world:</strong>
          </p>
          <ul>
            <li>Haas Business School, University of California at Berkeley, USA</li>
            <li>Nanyang Technological University, Singapore</li>
            <li>IE Business School in Madrid, Spain</li>
            <li>BI Norwegian Business School, Norway</li>
          </ul>
          <p><strong>*90% of classmates are from MNCs, with over 10 years working experience on average</strong>
          </p>
          <p><strong>*More than 1900 alumni in the BI-Fudan alumni network</strong>
          </p>
          <p><strong>*Over 50% of students recruited each year are referred by alumni, which reflects the program’s outstanding quality and students’ satisfaction</strong>
          </p>
          <p><strong>*A 2-year part-time program allows students to study without leaving work</strong>
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-8 col-md-offset-2">
      <div class='page-header page-header-with-icon'>
        <i class='fa fa-file-movie-o'></i>
        <h2>Event Video</h2>
        <p>Some important information regarding events</p>
      </div>
      <div class="video-container" style="width:100%;height:100%;max-width:1000px">
        <video width="100%" height="100%" id="player1" controls="controls" preload="metadata">
          <source src="http://greatcarrot.com/fudan/images/echo-hereweare.mp4" type="video/mp4" />
        </video>
      </div>
    </div>
  </div>
</div>