
<template>
    <div id="app-form">
    <img src="../../img/portfolio/circus.png" class="img-responsive img-centered" alt="">
    <form name="CreateNote" id="FormCreate" novalidate="">
        <div class="row control-group">
            <div class="form-group col-xs-12 floating-label-form-group controls">
                <label for="title">Title</label>
                <input type="text" class="form-control" placeholder="Title" id="TitleNote" required=""
                    data-validation-required-message="Please enter your name." aria-invalid="false">
                <p class="help-block text-danger"></p>
            </div>
        </div>
        <div class="row control-group">
            <div class="form-group col-xs-12 floating-label-form-group controls">
                <label for="message">Message</label>
                <textarea rows="5" class="form-control" placeholder="Message" id="message" required=""
                    data-validation-required-message="Please enter a message."></textarea>
                <p class="help-block text-danger"></p>
            </div>
        </div>
        <br>
        <div id="success"></div>
        <div class="row">
            <div class="form-group col-xs-12">
                <button type="submit" class="btn btn-success btn-lg">Add</button>
            </div>
        </div>
    </form>
    </div>
</template>

<script>
    import HelloWorld from './components/HelloWorld'

    export default {
        name: 'app-form'
    }
</script>