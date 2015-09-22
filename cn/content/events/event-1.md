+++
date = "2015-04-25T11:11:11+08:00"
draft = false
title = "Event 1"
day = "07"
month = "June"
location = "Shanghai Fudan University"
description = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean dictum varius ipsum"
time = "7pm"
type = "events"

+++
<div class='row'>
  <div class="col-sm-4">
    <div class="sidebar">
      <button class="btn btn-block sidebar-toggle" data-target=".sidebar-collapse" data-toggle="collapse" type="button">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <div class="sidebar-collapse collapse">
        <div class="col-sm-12">
          <div class='page-header page-header-with-icon'>
            <i class='fa fa-clock-o'></i>
            <h2>Event Details</h2>
          </div>
          <h3 class="name">Event Title - Event Location</h3>
          <h4 class="position">Event Date - Event Time</h4>
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
  </div>
  <div class='col-sm-8'>
    <div class='text-boxes'>
      <div class='row text-box'>
        <div class='col-sm-12'>
          <div class='page-header page-header-with-icon'>
            <i class='fa fa-info-circle '></i>
            <h2>Event Details</h2>
          </div>
          <p>Praesent sed viverra lacus. Aliquam congue porttitor ipsum sed vulputate. Nam lacus nunc, malesuada a massa sed, commodo placerat sem. Fusce rutrum bibendum adipiscing. Donec ac justo et metus vulputate faucibus. Mauris quis massa vel urna gravida vulputate vitae eu metus. Sed in leo sed metus tempus egestas a ac massa. Nunc cursus urna ac molestie cursus. Donec non sapien neque.</p>
          <p>Ut ipsum nisi, tempus ac iaculis ac, ultricies quis arcu. Integer tempor vitae lectus quis gravida. Mauris eget neque in lorem eleifend hendrerit vel et ligula. Ut ac viverra neque. In ullamcorper odio nec odio laoreet tempus. Cras eu sem eu purus posuere sagittis. In at dignissim quam. Pellentesque mollis, mi et condimentum hendrerit, felis justo interdum nulla, sed placerat nulla nibh et metus.</p>
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