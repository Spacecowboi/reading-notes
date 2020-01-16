Create Objects for each store, using a constructor function
    Pass in cookie shop data
        Location
        minCust/max
        cookiesPerHour
            CustomersPerHours * AverageCookiesPerCustomer
            CookieTotal
                For all hours, sum cookiePerHour

    Methods
        calc cookiesPerHour
        calc totalCookie
        calc customersEachHour

        Render Object data
            What is a table in HTML
                Header: Location name | displays each hour from our hours array | Total per location
                Body: displaying a matrix based on location * hours
                Footer: displaying "totals by hour" | display each total per hour | total by hour and location