# zxcvbn_go_nl_frequency
`zxcvbn_go_nl_frequency` is an extension package for the popular password strength estimator `zxcvbn`. This package specifically enhances `zxcvbn's` capabilities for the Dutch language by integrating a comprehensive Dutch frequency list. By incorporating this list, `zxcvbn` can now better analyze and assess the strength of passwords in Dutch contexts, providing more accurate and contextually relevant password strength feedback.

Props to: https://github.com/trustelem/zxcvbn for creating the zxcvbn package for go

## Usage
```go
package staartwind

import (
	"github.com/staartwind/zxcvbn_go_nl_frequency"
	"github.com/trustelem/zxcvbn/frequency"
)

func init() {
	frequency.FrequencyLists = zxcvbn_go_nl_frequency.zxcvbn_go_nl_frequency
}
```

# Contribution
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

# License
This project is licensed under the MIT License.