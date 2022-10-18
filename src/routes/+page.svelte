 <script>

 </script>
 
 <!-- Main Content - Products etc. -->
    <div class="container">
      <div class="row">
        <!-- Page Header -->
        <h2 class="mt-5">Products List</h2>
      </div>
      <div class="row">
        <div class="col-sm-2">
          <!-- Page Body Left Column (menu) -->
          <div id="categoryList" class="list-group">
            <!-- placeholders - replace with real category links -->
            <button
                class="category-link list-group-item list-group-item-action">
                All Products
            </button>
            
            <button
                class="category-link list-group-item list-group-item-action">
                Category A
            </button>
          </div>
        </div> <!-- End category col -->
        <div class="col-sm-10">
          <!-- Page Body Right Side (Content goes here) -->
          <div id="products">
            <table class="table table-striped table-bordered table-hover">
              <thead>
                <tr>
                  <th>id</th>
                  <th>name</th>
                  <th>description</th>
                  <th>stock</th>
                  <th>price</th>
                </tr>
              </thead>
              <tbody id="productRows">
                <!-- Product Rows to be inserted here -->
              </tbody>
            </table>
          </div>
        </div> <!-- End Product col -->
      </div> <!-- End Row -->
    </div> <!-- End Main Content-->