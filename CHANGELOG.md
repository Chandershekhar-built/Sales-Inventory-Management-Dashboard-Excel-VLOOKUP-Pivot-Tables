# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-05-28

### ✨ Initial Release - Complete Inventory Management Dashboard

#### Added
- 📊 **Dashboard Sheet** with 4 live KPI cards
  - Total Received aggregation
  - Total Dispatched aggregation
  - Quantity Available calculation
  - Stock Availability % donut chart

- 📈 **Visualization Suite**
  - 12-month stock availability trend chart (line chart with area fill)
  - Bottom-10 low-stock alert table with colour-coded status bars
  - Donut chart for inventory health percentage

- 🎛️ **Interactive Filtering**
  - Shelf slicer for location-based filtering (Shelf 1-5)
  - Product Name slicer for drill-down analysis
  - Multi-select capable slicers

- 📋 **Products Sheet**
  - 20 sample products (P-001 to P-020)
  - Master data with shelf assignments
  - Configurable re-order levels and quantities

- 📝 **Transactions Sheet**
  - Receipt/Dispatch transaction log
  - Date-stamped entries
  - Immutable audit trail

- ⚙️ **Calculation Sheet**
  - PivotTable engine for data aggregation
  - Monthly trend calculations (Jan-Dec)
  - Per-product availability metrics
  - Bottom-10 stock ranking

- 📚 **Documentation**
  - Comprehensive README.md
  - Detailed PROJECT_REPORT.md
  - CONTRIBUTING.md guidelines
  - MIT LICENSE file
  - CHANGELOG.md (this file)

#### Features
- ✅ Zero macros/VBA - works on any machine
- ✅ Excel 2016+ compatible (Windows & Mac)
- ✅ Fully extensible design
- ✅ Professional dashboard layout
- ✅ Real-time KPI updates on filter changes
- ✅ Automated low-stock alerts
- ✅ 12-month historical trend analysis

#### Technical
- Multi-sheet normalized data architecture
- GETPIVOTDATA formulas for dynamic references
- SUMIF/COUNTIF for conditional aggregations
- Dynamic named ranges for scalability
- Professional colour scheme and typography

### 📊 Data Included
- 500+ sample transaction records
- 20 products across 5 shelves
- 12 months of inventory history
- Realistic receipt/dispatch patterns

---

## [Unreleased]

### 🔜 Planned for Future Versions

#### Upcoming Features
- [ ] **Cost Tracking v1.1**
  - Cost per unit field
  - Total inventory valuation
  - Cost analysis by shelf

- [ ] **Supplier Management v1.2**
  - Supplier contact information
  - Lead time tracking
  - Cost comparison between suppliers

- [ ] **Automated Alerts v1.3**
  - Email notifications for critical stock
  - Slack integration
  - Custom alert thresholds

- [ ] **Forecasting v1.4**
  - Demand prediction
  - Seasonal trend analysis
  - Stock projection (30/60/90 days)

- [ ] **Multi-Warehouse v1.5**
  - Support for multiple locations
  - Inter-warehouse transfers
  - Consolidated reporting

- [ ] **Mobile App v2.0**
  - Barcode scanning
  - Real-time updates
  - Offline capability

- [ ] **Power BI Version v2.0**
  - Cloud-based dashboard
  - Advanced analytics
  - Real-time data refresh

#### Improvements
- [ ] Performance optimization for large datasets (10,000+ records)
- [ ] Enhanced UI/UX with modern design
- [ ] Accessibility improvements (screen reader support)
- [ ] Multi-language support
- [ ] Export to PDF functionality
- [ ] Advanced filtering capabilities

---

## 📝 Version Guidelines

### Semantic Versioning: MAJOR.MINOR.PATCH

- **MAJOR** (1.0.0 → 2.0.0): Breaking changes, major new features
- **MINOR** (1.0.0 → 1.1.0): New features, backwards compatible
- **PATCH** (1.0.0 → 1.0.1): Bug fixes, minor improvements

---

## 🔄 How to Track Changes

### For Contributors:

1. **Before Release:** Document your changes in [Unreleased] section
2. **When Features Merge:** Update the unreleased section
3. **At Release Time:** Move [Unreleased] to new version number

### Example Entry:

```markdown
## [1.1.0] - 2026-06-15

### Added
- Cost per unit tracking feature
- Inventory valuation calculations

### Fixed
- Slicer filtering bug on complex filters
- Chart rendering performance issue

### Changed
- Improved dashboard layout responsiveness
```

---

## 📞 Questions?

For questions about versioning or changes, open an issue or discussion.

---

<div align="center">

**[View All Releases](https://github.com/Chandershekhar-built/Sales-Inventory-Management-Dashboard-Excel-VLOOKUP-Pivot-Tables/releases)**

</div>
