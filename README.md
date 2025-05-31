# Performance Testing Project

## Overview
This project contains performance testing suite with automated reporting and test data management. The testing framework validates system performance against defined SLA thresholds and generates comprehensive aggregate reports.

## Project Structure
```
├── Aggregate_report.docx    # Detailed performance report (Word format)
├── Aggregate_report.pdf     # Performance report (PDF format)  
├── TestData.csv            # Test data for performance scenarios
└── README.md              # Project documentation
```

## Performance Criteria

### Error Rate Threshold
- **Maximum allowed error rate**: 10%
- **Current performance**: 0.00% ✅

### Response Time Requirements
- **90% of requests** must complete within **3 seconds**
  - Current: 556ms ✅
- **99% of requests** must complete within **5 seconds**  
  - Current: 692ms ✅

## Test Data Structure

The `TestData.csv` file contains user registration test data with the following fields:
- `fname` - First name
- `lname` - Last name  
- `gmail` - Email address
- `address1` - Primary address
- `address2` - Secondary address
- `city` - City
- `state` - State/Province
- `country` - Country
- `zipcode` - Postal code
- `phone` - Phone number
- `password` - User password
- `repeatpassword` - Password confirmation

## Getting Started

### Prerequisites
- Performance testing tool (JMeter, LoadRunner, etc.)
- CSV data processing capability
- Report generation tools

### Running Tests
1. Load the test data from `TestData.csv`
2. Configure your performance testing tool with the SLA thresholds
3. Execute the performance test scenarios
4. Generate reports using the provided templates

## Report Analysis

The aggregate reports show:
- **Error Rate**: 0.00% (Well within 10% threshold)
- **90th Percentile Response Time**: 556ms (Well within 3-second threshold)  
- **99th Percentile Response Time**: 692ms (Well within 5-second threshold)

## Performance Status
🟢 **All performance criteria are currently being met**

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-test-scenario`)
3. Commit your changes (`git commit -am 'Add new test scenario'`)
4. Push to the branch (`git push origin feature/new-test-scenario`)
5. Create a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions or support, please open an issue in this repository.

---
*Last updated: Performance metrics as of latest test run*
