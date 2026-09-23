# contributions-graph

A Go application that generates a beautiful contribution graph for the past 6 to 12 months directly **in your Terminal**.


**Go version:** Go 1.24.4

**External Dependencies:** `github.com/go-git/go-git/v5`

---

## How to Run

1. Clone the repository:
   ```bash
     git clone https://github.com/Mazinghorab/contributions-graph
   ```
   
2. Navigate into the directory:
   ```bash
     cd contributions-graph
   ```   

3.Build the application:
  ```bash
    go build -o GraphCont
  ```

4.Configure your local repositories and email:
  ```bash
    ./GraphCont -add /path/to/your/Directory
    ./GraphCont -email your@gmail.com
  ```
