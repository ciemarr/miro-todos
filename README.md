    <script type="text/javascript" src="https://miro.com/app/static/sdk.1.1.js"></script>
    <script type="text/javascript">
    miro.onReady(() => {
      miro.initialize({
        extensionPoints: {
          bottomBar: {
            title: 'Some title',
            svgIcon: '<circle cx="12" cy="12" r="9" fill="none" fill-rule="evenodd" stroke="currentColor" stroke-width="2"/>',
            onClick: () => {
              alert('Hi!')
            }
          }
        }
      })
    })
    </script>
