<template>

  <div class="container" id="events">

    <!-- add an event form -->
    <div class="col-sm-6">
      <div class="panel panel-default">
        <div class="panel-heading">
          <h3>Add an Event</h3>
        </div>
        <div class="panel-body">
          <div class="panel-heading">
            <h3>{{ greeting }}, World!</h3>
          </div>
          <div class="panel-body">

            <div class="form-group">
              <input class="form-control" placeholder="Event Name" v-model="event.name">
            </div>

            <div class="form-group">
              <textarea class="form-control" placeholder="Event Description" v-model="event.description"></textarea>
            </div>

            <div class="form-group">
              <input type="date" class="form-control" placeholder="Date" v-model="event.date">
            </div>

            <button class="btn btn-primary">Submit</button>

          </div>
        </div>
      </div>
    </div>

    <!-- show the events -->
    <div class="col-sm-6">
      <div class="list-group">

      </div>
    </div>
  </div>

</template>

<script>

</script>
